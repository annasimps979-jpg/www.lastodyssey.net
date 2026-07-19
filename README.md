<!--─┍┯┯━┯┷┿┳━━┳┿┿┯━━━┯━━━━━━━━━━━━━━━^^^━━━━━━━━━━━━━━━┯━━━┯┿┿┳━━┳┿┷┯━┯┯┑─-─-!>
<!-─-┼┼┬┼┼╶▞─┼╶-┼─╴▃┼┼╴▖╶─╶<(  N O T A   B E N E  )>╴─╴▗╶┼┼▃╶─┼-╴┼─▚╴┼┼┬┼┼--─-!>
<!-─-╞╧╧╧▙─╧╧╧╧┰▚╪╪╧═══╧═════════════^═^═^═════════════╧═══╧╪╪▞┰╧╧╧╧─▟╧╧╧╡░░─-!>
<!-─-│=     ▔ ▝ ▔                                             ▔ ▘ ▔      │░░─-!>
<!-─-│ This file is the “real” README.md file of the git repository, not │░░─-!>
<!-─-│ source text of a page on the Last Odyssey website. If one’s after │░░─-!>
<!-─-│ the file that corresponds to the content of the “/” document, the │░░─-!>
<!-─-│ file one seeks is a sibling of this one named ./index.md.         │░░─-!>
<!-─-┕━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┙░░─-!>
<!-─-─-░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░─-->

# Last Odyssey Website Source Repository

This repository’s content is the source text from which the static assets served
from [lastodyssey.net][LO_NET] endpoints are built.

The site is hosted by [GitHub Pages][PAGES], and [GitHub Actions][GH_ACTIONS] is
used to run the [static site generator][Jekyll] and deploy the static artifacts.

<!-- The comment which follows this is interpreted like a processing instruction
     by a tool called MarkdownTOC (https://github.com/naokazuterada/MarkdownTOC)
     which is realized as a Sublime Text plugin. It regenerates the TOC upon the
     file being saved in Sublime Text if it’s installed and activated. If one is
     editing this file in a manner that alters the document outline but is using
     an editor without MarkdownTOC, one should update the TOC manually to match.
                                                                             -->
<!-- MarkdownTOC autolink=1 -->

- [Branch Semantics](#branch-semantics)
- [Local Development](#local-development)
  - [Installing Dependencies](#installing-dependencies)
  - [Setting Localhost Alias](#setting-localhost-alias)
  - [Build, Watch, and Serve](#build-watch-and-serve)

<!-- /MarkdownTOC -->


## Branch Semantics

- [main][BRANCH_MAIN]: This is the default branch, source of truth for the state
  of the codebase itself. It’s the branch one would most often open PRs against.
- [prod][BRANCH_PROD]: This is the deployment branch, source of truth for what’s
  presently deployed to the production website. When updated, i.e. to align with
  the state of [main][BRANCH_MAIN], a [`push`][PUSH] [event][GH_EVENTS] triggers
  processing of the [`build-and-deploy-prod`][DEPLOY_PROD] [workflow][WORKFLOW],
  a schematic [yaml][YAML] file that’s effectively tantamount to a shell script.

When [main][BRANCH_MAIN] is ahead of [prod][BRANCH_PROD], this implies there are
updates to the site that haven’t yet been deployed, such as might occur when new
material is being developed which wouldn’t make sense if deployed incrementally.

Any other branches are ephemeral working branches — the sort one would typically
delete after a corresponding PR against [main][BRANCH_MAIN] has been merged.

## Local Development

### Installing Dependencies

The static site generator (SSG) used is [Jekyll], a [Ruby] [Gem], so to generate
and serve the static assets locally (with a filesystem watch), one needs to have
installed [Ruby] and [Bundler] — the latter being the package manager associated
the former. If one doesn’t already have these installed, one’s probably best off
installing an RVM ([Ruby] version manager) for your OS ([Windows][RVM_WINDOWS] /
[Linux & MacOS][RVM_UNIXISH]) that one would use to install [Ruby] and [Bundler]
but which would also allow one to freely switch between specific versions of ’em
— which may save ya pain down the line especially if you may end needing ’em fer
some other project down the line as well.

Once one’s all set on that front, cloned the repo locally, and with the repo dir
as yr CWD (current working directory), you’d first install the dependencies that
the [Gemfile](./Gemfile) specifies:

```sh
bundle install
```

### Setting Localhost Alias

Before running the dev server, open yr system’s [`hosts` file][HOSTS] (create it
if it doesn’t exist yet) to append the following line:

```hosts
127.0.0.1 www.lastodyssey.test
```

On Windows, the file path is `C:\Windows\System32\drivers\etc\hosts`. On POSIX-y
platforms, it’s at `/etc/hosts`. Note that on Windows, one can only edit it from
a process (e.g. a `notepad.exe` instance) running with administrator privileges.

> **Why do this?**
>
> If one were to visit http://127.0.0.1:80 without using that domain alias, none
> of the document subresources that are [fetched][FETCH_FETCH] with the `"cors"`
> [request mode][FETCH_MODE], e.g. [fonts][FETCH_FONT], would successfully load.

### Build, Watch, and Serve

Aight, head back to your repo directory (i.e. as CWD at the command line) so you
can kick off the build, the filesystem watch (it’ll regenerate assets as sources
are edited), and the local server:

```sh
bundle exec jekyll serve
```

> Note the indirection: we’re asking [Bundler] to execute the `jekyll serve` (or
> `jekyll s`) command, not doing so directly. We may not have [Jekyll] installed
> globally and available to us via the `PATH`, and if we do, its version may not
> be the same as the version specified in the [Gemfile](./Gemfile).

If all went well, the static assets will be generated and stored as files in the
`./_site` directory at the repo’s root, a filewatch will begin to monitor source
for changes that imply the need to regenerate assets, and the local HTTP server,
using [WEBRick], will begin listening on port 80, such that one can now navigate
to [`http://www.lastodyssey.test`][LO_DEV] to work on the site locally. If there
was an error message regarding port 80 being unavailable, however, one oughta go
to [`./_config.yml`](./_config.yml) and change the `port:` value from 80 to 8080
or another “high” port; then try it again. If the server runs successfully after
the change, the origin would look like `http://lastodyssey.test:8080`, i.e. with
the non-special port you selected as an explicit suffix after a colon. Unless yr
already running another HTTP server locally, on Windows you can normally use the
real HTTP port, i.e. 80, but on MacOS or Linux, iirc, it probably wouldn’t work.

> At the time of writing, only Anna and Billy have been working in the codebase,
> and both of ’em do so in Windows environments. Since we’ve not attempted local
> development in Linux or MacOS environments, if there are any issues preventing
> it from workin’ as expected on those platforms, we just wouldn’t be aware yet.

Note that in local development the scheme is `http`, not `https`. This does mean
there are materially different runtime behaviors beyond just a different origin,
so there are some things that cannot be tested locally in development right now,
e.g. service workers. In the future, we may wana add a devcert tool to this mix.

[Bundler     ]: https://bundler.io/
[Gem         ]: https://rubygems.org/
[Jekyll      ]: https://jekyllrb.com/docs/
[Ruby        ]: https://www.ruby-lang.org/
[WEBrick     ]: https://github.com/ruby/webrick

[BRANCH_MAIN ]: https://github.com/annasimps979-jpg/www.lastodyssey.net/tree/main
[BRANCH_PROD ]: https://github.com/annasimps979-jpg/www.lastodyssey.net/tree/prod
[DEPLOY_PROD ]: https://github.com/annasimps979-jpg/www.lastodyssey.net/blob/main/.github/workflows/build-and-deploy-prod.yml
[FETCH_FETCH ]: https://fetch.spec.whatwg.org/#concept-fetch
[FETCH_FONT  ]: https://drafts.csswg.org/css-fonts/#font-fetching-requirements
[FETCH_MODE  ]: https://fetch.spec.whatwg.org/#concept-request-mode
[GH_ACTIONS  ]: https://docs.github.com/en/actions
[GH_PAGES    ]: https://docs.github.com/en/pages
[GH_PAGES_GEM]: https://github.com/github/pages-gem
[GH_EVENTS   ]: https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows
[GH_WORKFLOW ]: https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax
[HOSTS       ]: https://en.wikipedia.org/wiki/Hosts_(file)
[LO_DEV      ]: http://www.lastodyssey.test
[LO_NET      ]: https://lastodyssey.net
[RVM_UNIXISH ]: https://rvm.io/
[RVM_WINDOWS ]: https://github.com/magynhard/rvm-windows#readme
