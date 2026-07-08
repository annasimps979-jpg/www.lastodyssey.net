# Warrior Creation

[GMs](/srd/glossary#term-gm) who want to introduce warriors not included in the [Example Warriors](/srd/warriors/examples) section have a few options.  First, they could take a pre-existing warrior and change it superficially, either by altering its creature or [elements](/srd/combat/elements#term-element) and the elements of its [abilities](/srd/glossary#term-ability) and then changing its name and appearance.  They could also take an existing warrior and change its abilities.  Whatever the GM decides, it is recommended that they not repeat the same warrior too many times.  This is partially to maintain the sense of danger and discovery for [players](/srd/glossary#term-player), and partially because learning about the abilities and [statistics](/srd/glossary#term-statistic) of the warriors that [Heroes](/srd/glossary#term-hero) will face on the road is a core part of the experience of Last Odyssey.

## Warrior Properties

*  The _<dfn id = "term-power-level">power level</dfn>_ of an warrior is a measure of its power relative to its [tier](/srd/heroes/creation#term-tier).  _<dfn id = "term-normal-warrior">Normal</dfn>_ warriors are about as powerful as a Hero, _<dfn id = "term-elite-warrior">Elite</dfn>_ warriors are a match for the entire [party](/srd/glossary#term-party), and [Antagonists](/srd/anima/antagonists) are powerful bosses that are a serious challenge for any party.
*  The _<dfn id = "term-creature-type">creature type</dfn>_ of an warrior is a single word that best describes the type of living being they are in the context of the setting.  There are a few special items, such as weapons with the Slayer feature, that interact with an warrior's creature type.
*  An warrior's _element_ determines the damage that different elemental attacks do to them.
*  An warrior's _tier_ indirectly determines their [combat](/srd/combat) [statistics](/srd/heroes/numbers#term-statistic) by setting the number of [attribute](/srd/glossary#term-attribute) points available to allocate to determine their statistics.
*  _Aggression_ is a measure of how vicious an warrior is in close quarters, and contributes to an warrior's [Physical Attack](/srd/heroes/numbers#term-strike), [Initiative](/srd/heroes/numbers#term-initiative), and [Physical Accuracy](/srd/heroes/numbers#term-physical-accuracy).
*  _Toughness_ is a measure of how much damage an warrior can take, and contributes to an warrior's [Physical Defense](/srd/heroes/numbers#term-physical-defense), [Resistance](/srd/heroes/numbers#term-resistance), and [Health](/srd/heroes/numbers#term-health).
*  _Magic_ is a measure of how adept an warrior is at dealing with magic, and contributes to an warrior's [Magical Attack](/srd/heroes/numbers#term-spell), [Magical Defense](/srd/heroes/numbers#term-magical-defense), [Magical Accuracy](/srd/heroes/numbers#term-magical-accuracy), and [Mana](/srd/heroes/numbers#term-mana).
*  _Cunning_ is a measure of how clever and evasive an warrior is, and contributes to an warrior's [Evasion](/srd/heroes/numbers#term-evasion), [Magical Accuracy](/srd/heroes/numbers#term-magical-accuracy), and [Status Accuracy](/srd/heroes/numbers#term-status-accuracy), and [Initiative](/srd/heroes/numbers#term-initiative).

## Setting Attributes

When creating a new warrior, the GM must spend a fixed amount of points on each of these attributes that depends on the warrior's tier and its power level.  At tier 1, Normal warriors have 6 points to distribute, Elite warriors have 8, and each [Form](/srd/anima/antagonists/defeat#term-form) of an Antagonist has 10.  Each additional tier grants 2 more points to Normal warriors, 3 more points to Elite warriors, and 4 more points to Antagonists.  The minimum value that an warrior can have in each of their attributes is 0.  The maximum value that a Normal warrior can have in a given attribute is 10, the maximum value an Elite can have is 15, and the maximum that an Antagonist can have is 20.  In addition to attribute points, the Health, Mana, and Initiative of all warriors are adjusted by a number called the warrior's _<dfn id = "term-tier-multiplier">tier multiplier</dfn>._  The tier multipliers for a Normal warrior are 5 for their Health and Mana and 1 for their Initiative, Elites have multipliers of 10 for their Health and Mana and 2 for their Initiative, and Antagonists have 20 for their Health and Mana and 2 for their Initiative.

## Calculating Statistics

Once attribute points have been allocated, the warrior's combat statistics are determined by their attributes by the following formulae:
*  Health = (Toughness)x5 + (Tier)x(Tier Multiplier).
*  Mana = (Magic)x5 + (Tier)x(Tier Multiplier).
*  Initiative = (Aggression) + (Cunning) + (Tier)x(Tier Multiplier).
*  Physical Attack = (Aggression)x2.
*  Magical Attack = (Magic)x2.
*  Physical Defense = (Toughness).
*  Magical Defense = (Magic).
*  Evasion = (Cunning).
*  Resistance = (Toughness).
*  Physical Accuracy = (Aggression)x2.
*  Magical Accuracy = (Cunning) + (Magic).
*  Status Accuracy = (Cunning)x2.

Unlike Heroes, warriors' maximum [HP](/srd/heroes/numbers#term-hp) and [Shell](/srd/combat/shells) are distinct values.  The total combined HP plus Shell of a single warrior is equal to its Health, and the ratio of its HP to its Shell is equal to the ratio of its Toughness plus its Aggression to its Magic plus its Cunning.  For example, an warrior with an Aggression of 4, a Toughness of 5, a Magic of 3, and a Cunning of 3 would have HP equal to three fifths of its Health and Shell equal to two fifths of its Health.  If the value calculated isn't exact (and it often won't be) just round the warrior's Health and Shell to the nearest integer.  Once statistics are calculated, the GM can then adjust them if they like.  When doing so, they should remember that 1 point of Physical Defense, Magical Defense, Evasion, or Resistance is worth 2 points of Physical Attack, Magical Attack, Physical Accuracy, Magical Accuracy, Initiative, or Status Accuracy, and also worth 5 points of Health or Mana.

## Setting Abilities

After setting the combat statistics of an warrior, the GM should then choose its abilities.  Normal warriors should get two abilities, and Elite warriors should get four, while every Form of an Antagonist can have as many as appropriate, although 6-10 is a good median range.  If the warrior does not have a [basic attack](/srd/combat/round#term-basic-attack), they receive an extra ability.  Examples of warrior abilities can be drawn from the lists of abilities for [character](/srd/glossary#term-character) [roles](/srd/heroes/roles) and [archetypes](/srd/heroes/archetypes) and from the abilities of all other warriors in the [Example Warriors](/srd/warriors/examples) section of their tier or below.  In the case of character abilities, warriors can only have access to abilities associated with a rank of an archetype or role equal to twice their tier.  In addition to active abilities, warriors may also have [passive](/srd/combat/attacks#term-passive) abilities, which are extra effects that activate when certain conditions are met.  For example, an warrior might have an ability that makes them immune to water damage, or might gain the Focused [status](/srd/combat/statuses) when they lose their Shell.  GMs are also encouraged to come up with passives on their own.

## Behavior and Tactics

After an warrior's combat statistics and abilities have been determined, they are technically ready to be deployed into a [campaign](/srd/glossary#term-campaign).  However, GMs should remember that an warrior is a living entity that makes decisions based on imperatives other than [battle](/srd/glossary#term-battle) tactics.  The last thing they do, then, should be to determine the warrior's behavior.  At minimum, GMs should note down what other warriors they will fight alongside, if any, and what pattern of abilities they will use in combat.  For example, an warrior that is mindless and aggressive might attack any of their opponents in the [front row](/srd/combat/starting#term-front-row) at random, while a group of warriors using squadron tactics will rotate out who is in the front row based on their remaining HP and Shell.  Once this is done, set the warrior's [item table](/srd/combat/ending#term-item-table), and it is complete.

## Summary

In total, GMs creating a new warrior should complete the following steps:
1.  Determine its tier and power level.
2.  Determine its creature type.'
3.  Determine its element.
4.  Determine its attributes.
5.  Assign combat statistics based on the values of its attributes, and adjust as needed.
6.  Determine its abilities.
7.  Determine its item table.
8.  Determine its behavior in and out of combat.
