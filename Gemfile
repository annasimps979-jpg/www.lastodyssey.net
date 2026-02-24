# GEMFILE ######################################################################
#
# The `source` declaration specifies an origin fer Bundler to lookup and install
# Ruby dependencies (aka “gems”, the Ruby ecosystem’s cutesy name fer what would
# be called modules, packages, or libraries in most other languages) from.

source "https://rubygems.org"

# The central dependency here is the `github-pages` gem. Although it’s nominally
# a Jekyll plugin, its own dependency graph includes Jekyll and all other Jekyll
# plugins that are part of what the GitHub Pages service is said to be providin’
# out of the box. Because we dunt get to control which version of `github-pages`
# runs in practice when deploying, we only specify a lower bound fer its version
# (i.e. we want what’s current at the time of writing *or* something subsequent)
# and we dunt wanna specify its own dependencies ourselves at all; instead, what
# we want is fer it to remain “in charge of the show” to whatever extent we can.
# pretrt

gem "github-pages", "~> 232", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# On Unix-heritage operating systems like Linux and Mac OS, the IANA timezone db
# is globally available via /usr/share/zoneinfo/. Though Windows also exposes TZ
# data, it doesn’t do so in the same way, so fer local development on Windows we
# need to install two additional dependencies to make the same data available in
# the expected format.

platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
