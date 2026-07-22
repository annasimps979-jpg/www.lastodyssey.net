---
title: Battle Items

permalink: /srd/economy/items/battle

abstract: >-
    The items used in combat.
---

_<dfn id = "term-battle-item">Battle items</dfn>_ are a variety of item that is usable during [combat](/srd/combat).  Some battle items reproduce the effects of an ability such as [Heal](/srd/heroes/roles/healer) or [Restore Mana](/srd/heroes/archetypes/priest), while others have more unique effects.  Each individual battle item, once used, is expended and disappears from the [party](/srd/glossary#term-party) inventory.  All battle items cost 1 [AP](/srd/combat/round#term-ap) to use unless otherwise specified.

## Battle Item Effects
Each battle item has a discrete effect that it induces during combat.  In theory, multiple items could lead to the same effect.  Rather than having a fixed list of items, Last Odyssey has a fixed set of item effects that could be caused by multiple items.  This is for two reasons.  The first is that the value of an item to the [players](/srd/glossary#term-player) is determined by what it does, and not what it looks like, and this is reflected in the item's cost.  The second is that the item that produces an effect in one setting may be different to its equivalent in another.  For example, in a sci-fi setting healing items may take the form of injectors or medkits, while in a fantasy setting they could take the form of healing potions or poultices.

Every item's base cost is defined by its _<dfn id = "term-item-effect">effect</dfn>_ and how potent that effect is, the latter of which is determined by its Grade, and any enhancements.  There are three Grades of item: Novice, Standard, and Expert.  Some items have effects that depend on their Grade, while others do not.  In the rulebook, the former are referred to as _<dfn id = "term-leveled-item-effect">leveled</dfn>,_ while the latter are referred to as _<dfn id = "term-non-leveled-item-effect">non-leveled</dfn>._  If an item is leveled, its effect and its cost are determined by its Grade, whereas non-leveled items do not have a Grade.  Each additional level of Grade multiplies the cost of the battle item by ten.  For example, if the Novice version of an item costs 5 [<abbr title = "currency">¤</abbr>](/srd/economy/currency#term-cr), then the Standard version will cost 50 <abbr title = "currency">¤</abbr> and the Expert version will cost 500 <abbr title = "currency">¤</abbr>.

### Leveled Item Effects

|Effect|Base Cost|Description|
|:-|:-|:-|
|Restore HP|1 <abbr title = "currency">¤</abbr>|When used, this item restores a fixed amount of [HP](/srd/heroes/numbers#term-hp) to a single [character](/srd/glossary#term-character).  If it is Novice, it restores 10 HP, if it is Standard it restores 20, and if it is Expert it restores 30.|
|Restore MP|3 <abbr title = "currency">¤</abbr>|When used, this item restores a fixed amount of [MP](/srd/heroes/numbers#term-mp) to a single character.  If it is Novice, it restores 10 MP, if it is Standard it restores 20, and if it is Expert it restores 30.|
|Physical Damage|5 <abbr title = "currency">¤</abbr>|When used, this item deals [base](/srd/glossary#term-base) [colorless](/srd/combat/elements#term-colorless) physical damage to a single character that can be affected by damage multipliers.  If it is Novice it deals 2 damage, if it is Standard it deals 5 damage, and if it is Expert it deals 10 damage.|
|Magical Damage|5 <abbr title = "currency">¤</abbr>|When used, this item deals base colorless [magical damage](/srd/combat/attacks#term-magical-damage) to a single character that can be affected by damage multipliers.  If it is Novice it deals 2 damage, if it is Standard it deals 5 damage, and if it is Expert it deals 10 damage.|
|Special Damage|7 <abbr title = "currency">¤</abbr>|When used, this item deals base [elemental](/srd/combat/elements#term-element) physical damage of a specified type to a single character that can be affected by damage multipliers.  If it is Novice it deals 2 damage, if it is Standard it deals 5 damage, and if it is Expert it deals 10 damage.|
|Elemental Damage|7 <abbr title = "currency">¤</abbr>|When used, this item deals base elemental magical damage of a specified type to a single character that can be affected by damage multipliers.  If it is Novice it deals 2 damage, if it is Standard it deals 5 damage, and if it is Expert it deals 10 damage.|
|Hex|9 <abbr title = "currency">¤</abbr>|When used, this item inflicts a [hex](/srd/combat/glamors#term-hex) of the specified type.  If it is Novice, it hexes by one level on the [Bonus Tracker](/srd/combat/glamors#term-bonus-tracker), if it is Standard it hexes by two, and if it is Expert it hexes by three.|
|Charm|9 <abbr title = "currency">¤</abbr>|When used, this item applies a [charm](/srd/combat/glamors#term-charm) of the specified type.  If it is Novice, it charms by one level on the Bonus Tracker, if it is Standard it charms by two, and if it is Expert it charms by three.|
|Inflict Status|12 <abbr title = "currency">¤</abbr>|When a character uses this item, it activates a [sleight](/srd/combat/attacks#term-sleight) against the target's [Resistance](/srd/heroes/numbers#term-resistance) that inflicts the specified [status](/srd/combat/statuses) on a hit.  If the item is Novice, subtract 5 from the result on the [hit die](/srd/combat/attacks#term-hit-die).  If the item is Standard, subtract 10 from the result, and if the Expert then subtract 15 from the result.|
|Revive|15 <abbr title = "currency">¤</abbr>|When a character uses this item, the targeted character is revived from being [downed](/srd/combat/injuries#term-downed).  If the item is Novice, they are revived to 1 HP, if the item is Standard, they are revived to half their maximum HP, rounded down, and if the item is Expert then they are revived to their current maximum HP.|

### Non-Leveled Item Effects

|Effect|Base Cost|Description|
|:-|:-|:-|
|Scan|10 <abbr title = "currency">¤</abbr>|This item applies the [Artificer's](/srd/heroes/archetypes/artificer) Scan ability to a single target, revealing all current relevant information about it.|
|Remove Hexes|15 <abbr title = "currency">¤</abbr>|This item removes all hexes from a single character.|
|Remove Status|20 <abbr title = "currency">¤</abbr>|This item removes a status of the corresponding element from a single character.|
|Negate Resistances|50 <abbr title = "currency">¤</abbr>|This item negates all of a target's elemental resistances, which is to say that no elemental multiplier for any attack that hits it can be less than 1, until the beginning of the target's next [turn](/srd/combat/round#term-turn).|
|Block Physical Damage|100 <abbr title = "currency">¤</abbr>|The next time the target of this item would otherwise take physical damage, they do not take any damage instead.|
|Block Magical Damage|400 <abbr title = "currency">¤</abbr>|The next time the target of this item would otherwise take magical damage, they do not take any damage instead.|
|Shell|10 <abbr title = "currency">¤</abbr>|The target of this item gains 10 Shell of the corresponding element.|
|Haste|800 <abbr title = "currency">¤</abbr>|The target of this item becomes [Hasted](/srd/heroes/roles/support) for three subsequent rounds.  This still cannot stack with any other applications of Hasted.|
|Slow|900 <abbr title = "currency">¤</abbr>|The target of this item becomes [Slowed](/srd/heroes/roles/saboteur) for three subsequent rounds.  This still cannot stack with any other applications of Slowed.|
|Summon Warrior|1000x(Tier of summoned warrior)|When a character uses this item, it summons a [warrior](/srd/warriors) of a specified type to fight as an ally on their side.  The first time it can take its turn is during the [round](/srd/combat/round#term-round) after it was summoned, but it can be targeted as soon as it is summoned.|

## Item Enhancements
In addition to their base effects, some items have special effects called _<dfn id = "term-item-enhancement">enhancements</dfn>_ that change when and how they can be used and whom they target on the battlefield.  Most items will have only one enhancement, since enhancements that change their target are mutually exclusive, but some extremely rare items could have multiple.  Each enhancement to an item multiplies its base cost by an amount given in the enhancement description.  The possible enhancements are as follows:

|Enhancement|Description|
|:-|:-|
|All|This item affects all characters on the battlefield.  Multiplies base cost by 2.|
|Row|This item affects all characters on a single [row](/srd/combat/starting#term-row).  When a character uses this item, they may choose which row it affects.  Multiplies base cost by 5.|
|Multi|This item affects all characters on the side it targets.  Items that target the user's allies' side will affect all allies, while items that target their opponents' side will affect all opponents.  Multiplies base cost by 10.|
|Dual|This item has the effect of two different items at once.  The total cost of the item is the base cost of each item effect added together, multiplied by 5.|
|Delay|When a character uses this item, it does not trigger immediately.  Instead, its effect happens during the [Effect Phase](/srd/combat/round#term-effect-phase) of the round.  Multiplies cost by 0.75, rounded down.|
|Random|If possible, then, when a character uses this item, it inflicts a random effect based on casting a result from the [Random Element Table](/srd/combat/random-tables#term-random-element-table) or [Random Statistic Table](/srd/combat/random-tables#term-random-statistic-table), depending on the item in question. If the item being generated does not have either of these types, this enhancement counts as having none at all.  Multiplies cost by 1.|

Enhancements cannot be applied to the Summon Warrior item.

## Example Battle Items

|Name|Grade|Effect|Enhancements|Cost|
|:-|:-|:-|:-|:-|
|Throwing Knife|Novice|Physical Damage|N/A|5 <abbr title = "currency">¤</abbr>|
|Elixir|Novice|Restore HP/Restore MP|Dual|20 <abbr title = "currency">¤</abbr>|
|Smoke Bomb|Novice|Charm Evasion|All|18 <abbr title = "currency">¤</abbr>|
|Shark Tooth Charm|Standard|Special Damage (Water)|N/A|70 <abbr title = "currency">¤</abbr>|
|Smelling Salts|Standard|Revive|Row|750 <abbr title = "currency">¤</abbr>|
|Poison Dart|Standard|Inflict Poisoned|Delay|90 <abbr title = "currency">¤</abbr>|
|Experimental Combat Stim|Expert|Charm [Physical Attack](/srd/heroes/numbers#term-strike)/Charm [Physical Accuracy](/srd/heroes/numbers#term-physical-accuracy)|Dual|9000 <abbr title = "currency">¤</abbr>|
|Exquisite Fire Gem|Expert|Elemental Damage (Fire)|Multi|7000 <abbr title = "currency">¤</abbr>|
|Mandragora|N/A|Summon Warrior ([Dryad](/srd/warriors/examples/tier/02))|N/A|2000 <abbr title = "currency">¤</abbr>|

## Battle Item Generation
At times, there is a need to quickly create new items.  If the <abbr title="game master">[GM](/srd/glossary#term-gm)</abbr> needs to reward the players with a new battle item and doesn't have anything on hand, they can follow a relatively simple process to create a new one.  First, cast d20 and consult the table below:

|Result|Effect|
|:-|:-|
|1|Restore HP|
|2|Restore MP|
|3|Physical Damage|
|4|Magical Damage|
|5|Special Damage|
|6|Elemental Damage|
|7|Hex|
|8|Charm|
|9|Inflict Status|
|10|Revive|
|11|Scan|
|12|Remove Hexes|
|13|Remove statuses|
|14|Negate Resistances|
|15|Block Physical Damage|
|16|Block Magical Damage|
|17|Shell|
|18|Haste|
|19|Slow|
|20|Summon Creature|

The result that matches the result on the die is the effect of the item in question.  If the item's effect is leveled, determine the item Grade.  Novice items are appropriate for characters of levels 1-4, Standard items are for characters of levels 5-7, and Expert items are appropriate for characters of levels 8-10, but the item costs are balanced such that characters of different tiers can still use items of a lower or higher Grade without the balance of combat being destroyed.

After the item's effect has been determined, cast the [outcome die](/srd/glossary#term-outcome-die).  If the result is a 7 or above, the item does not have any enhancements.  If the result is 1-6, the enhancement is shown on the table below:

|Result|Enhancement|
|:-|:-|
|1|All|
|2|Row|
|3|Multi|
|4|Dual|
|5|Delay|
|6|Random|

For the Dual effect, cast the outcome die again for the item's second effect.  Then, if relevant, cast the die on the Random Element Table to determine the element of the item's effect.  If the item is a Charm or Hex item, use the [Random Statistic Table](/srd/combat/random-tables#term-random-statistic-table) to see what [statistic](/srd/glossary#term-statistic) it affects.  If the item is a Summon Creature item, choose a warrior from the [Example Warriors](/srd/warriors/examples) section or create one of the appropriate tier.

The last thing to do when creating an item is to calculate its <abbr title = "currency">¤</abbr> value and give it tangible existence in the game world.  A good rule of thumb is that an item should have a means by which character activate it, a physical form, and a container, such as a glass vial or a ball of clay.
