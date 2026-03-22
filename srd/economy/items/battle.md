# Battle Items

_<dfn id = "term-battle-item">Battle items</dfn>_ are a variety of inventory item that is usable during [combat](/srd/combat).  Some battle items reproduce the effects of an ability such as Heal or Restore Mana, while others have more unique effects.  Each individual item, once used, is expended and disappears from the [party](/srd/key-terms#term-party) inventory.  All battle items cost 1 [AP](/srd/combat/round#term-ap) to use unless otherwise specified.

## Battle Item Effects
Each battle item has a discrete effect that it induces during combat.  In theory, multiple items could lead to the same effect.  Rather than having a fixed list of items, Last Odyssey has a fixed set of item effects that could be caused by multiple items.  This is for two reasons.  The first is that the value of an item to the [players](/srd/key-terms#term-player) is determined by what it does, and not what it looks like, and this is reflected in the item's cost.  The second is that the item that produces an effect in one setting may be different to its equivalent in another.  For example, in a sci-fi setting healing items may take the form of injectors or medkits, while in a fantasy setting they could take the form of healing potions or poultices.

Every item's base cost is defined by its _<dfn id = "term-item-effect">effect</dfn>,_ how potent that effect is, which is determined by its item Quality, and any enhancements.  There are three Qualities of item: Mundane, Rare, and Expert.  Some items have effects that depend on their Quality, while others do not.  In the rulebook, the former are referred to as _<dfn id = "term-leveled-item-effect">leveled</dfn>,_ while the latter are referred to as _<dfn id = "term-non-leveled-item-effect">non-leveled</dfn>._  If an item is leveled, its effect and its cost are determined by its Quality, whereas non-leveled items do not have a Quality rating.  Each additional level of Quality multiplies the cost of the item by ten.  For example, if the Mundane version of an item costs 5 [cr](/srd/economy#term-cr), then the Rare version will cost 50 cr and the Expert version will cost 500 cr.

### Leveled Item Effects

|Effect|Base Cost|Description|
|:-|:-|:-|
|Restore HP|1 cr|When used, this item restores a fixed amount of [HP](/srd/heroes/attributes-and-statistics#term-hp) to a single [character](/srd/key-terms#term-character).  If it is Mundane, it restores 5 HP, if it is Rare it restores 10, and if it is Expert it restores 20.|
|Restore MP|3 cr|When used, this item restores a fixed amount of [MP](/srd/heroes/attributes-and-statistics#term-mp) to a single character.  If it is Mundane, it restores 10 MP, if it is Rare it restores 20, and if it is Expert it restores 30.|
|Physical Damage|5 cr|When used, this item deals [base](/srd/key-terms#term-base) [colorless](/srd/combat/elemental-types#term-colorless) physical damage to a single character that can be affected by damage modifiers.  If it is Mundane it deals 5 damage, if it is Rare it deals 10 damage, and if it is Expert it deals 20 damage.|
|Magical Damage|5 cr|When used, this item deals base colorless magical damage to a single character that can be affected by damage modifiers.  If it is Mundane it deals 5 damage, if it is Rare it deals 10 damage, and if it is Expert it deals 20 damage.|
|Special Damage|7 cr|When used, this item deals base [elemental](/srd/combat/elemental-types#term-elemental-type) physical damage of a specified type to a single character that can be affected by damage modifiers.  If it is Mundane it deals 5 damage, if it is Rare it deals 10 damage, and if it is Expert it deals 20 damage.|
|Elemental Damage|7 cr|When used, this item deals base elemental magical damage of a specified type to a single character that can be affected by damage modifiers.  If it is Mundane it deals 5 damage, if it is Rare it deals 10 damage, and if it is Expert it deals 20 damage.|
|Debuff|9 cr|When used, this item inflicts a [debuff](/srd/combat/buffs-and-debuffs#term-debuff) of the specified type.  If it is Mundane, it debuffs by one level on the [Bonus Tracker](/srd/combat/buffs-and-debuffs#term-bonus-tracker), if it is Rare it debuffs by two, and if it is Expert it debuffs by three.|
|Buff|9 cr|When used, this item applies a [buff](/srd/combat/buffs-and-debuffs#term-buff) of the specified type.  If it is Mundane, it buffs by one level on the Bonus Tracker, if it is Rare it buffs by two, and if it is Expert it buffs by three.|
|Inflict Status|12 cr|When you use this item, use a [status-inflicting ability](/srd/combat/attacking-and-defending#term-status-inflicting-ability) against the target's [Resistance](/srd/heroes/attributes-and-statistics#term-resistance) to determine whether or not the specified [status](/srd/combat/statuses) is inflicted.  If the item is Mundane, do not subtract anything from the result.  If the item is Rare, subtract 2 from the result, and if the Expert then subtract 5 from the result.|
|Revive|15 cr|When you use this item, the targeted character is revived from being [downed](/srd/combat/death-and-injury#term-downed).  If the item is Mundane, they are revived to 1 HP.  If the item is Rare they are revived to half their maximum HP, rounded down, and if the item is Expert then they are revived to their current maximum HP.|

### Non-Leveled Item Effects

|Effect|Base Cost|Description|
|:-|:-|:-|
|Scan|10 cr|This item applies the [Artificer's](/srd/heroes/archetypes/artificer) Scan ability to a single target, revealing all current relevant information about it.|
|Remove Debuffs|15 cr|This item removes all debuffs from a single character.|
|Remove Status|20 cr|This item removes a status of the specified type from a single character.|
|Negate Resistances|50 cr|This item negates all of a target's elemental resistances until the beginning of the target's next [turn](/srd/combat/round#term-turn).|
|Block Physical Damage|100 cr|The next time the target of this item would otherwise take physical damage, they do not take any damage instead.|
|Block Magical Damage|400 cr|The next time the target of this item would otherwise take magical damage, they do not take any damage instead.|
|Shell|10 cr|The target of this item gains 10 Shell of the corresponding elemental type.|
|Haste|800 cr|The target of this item becomes [Hasted](/srd/heroes/roles/support).  This still cannot stack with any other applications of Hasted.|
|Slow|900 cr|The target of this item becomes [Slowed](/srd/heroes/roles/saboteur).  This still cannot stack with any other applications of Slowed.|
|Summon Creature|1000x(Tier of summoned creature)|When you use this item, it summons a creature, usually an [enemy](/srd/enemies) of some type, to fight as an ally on your side.  The first time it can take its turn is during the [round](/srd/combat/round#term-round) after you summoned it, but it can be targeted as soon as it is summoned.|

## Item Enhancements
In addition to their base effects, some items have special effects called _<dfn id = "term-item-enhancement">enhancements</dfn>_ that change when and how they can be used and whom they target on the battlefield.  Most items will have only one enhancement, since enhancements that change their target are mutually exclusive, but some extremely rare items could have multiple.  Each enhancement to an item multiplies its base cost by an amount given in the enhancement description.  The possible enhancements are as follows:

|Enhancement|Description|
|:-|:-|
|All|This item affects all characters on the battlefield.  Multiplies base cost by 2.|
|Row|This item affects all characters on a single [row](/srd/combat/starting#term-row).  When you use the item, you can choose which row it affects.  Multiplies base cost by 5.|
|Multi|This item affects all characters on the side it targets.  Items that target allies will affect all allies, while items that target enemies will affect all enemies.  Multiplies base cost by 10.|
|Dual|This item has the effect of two different items at once.  The total cost of the item is the base cost of each item added together, multiplied by 5.|
|Delay|When you use this item, it does not trigger immediately.  Instead, its effect happens during the [Effect Phase](/srd/combat/round#term-effect-phase) of the round.  Multiplies cost by 0.75, rounded down.|
|Random|When you use this item, it inflicts a random effect based on your result on the [Random Element Table](/srd/extras/random-tables#term-random-element-table).|

## Example Battle Items

|Name|Quality|Effect|Enhancements|Cost|
|:-|:-|:-|:-|:-|
|Throwing Knife|Mundane|Physical Damage|N/A|5 cr|
|Elixir|Mundane|Restore HP/Restore MP|Dual|20 cr|
|Smoke Bomb|Mundane|Buff Evasion|All|18 cr|
|Shark Tooth Charm|Rare|Special Damage (Water)|N/A|70 cr|
|Smelling Salts|Rare|Revive|Row|750 cr|
|Poison Dart|Rare|Inflict Toxin|Delay|90 cr|
|Experimental Combat Stim|Expert|Buff [Physical Attack](/srd/heroes/attributes-and-statistics#term-physical-attack)/Buff [Physical Accuracy](/srd/heroes/attributes-and-statistics#term-physical-accuracy)|Dual|9000 cr|
|Exquisite Fire Gem|Expert|Elemental Damage (Fire)|Multi|7000 cr|
|Mandragora|N/A|Summon Creature (Dryad)|N/A|4000 cr|

## Battle Item Generation
At times, there is a need to quickly create new items.  If the [GM](/srd/key-terms#term-gm) needs to reward the players or their enemies with a new battle item and doesn't have anything on hand, they can follow a relatively simple process to create a new one.  First, cast d20 and consult the table below:

|Result|Effect|
|:-|:-|
|1|Restore HP|
|2|Restore MP|
|3|Physical Damage|
|4|Magical Damage|
|5|Special Damage|
|6|Elemental Damage|
|7|Debuff|
|8|Buff|
|9|Inflict Status|
|10|Revive|
|11|Scan|
|12|Remove Debuffs|
|13|Remove statuses|
|14|Negate Resistances|
|15|Block Physical Damage|
|16|Block Magical Damage|
|17|Shell|
|18|Haste|
|19|Slow|
|20|Summon Creature|

The result that matches the result on the die is the effect of the item in question.  If the item's effect is leveled, determine the item Quality.  Mundane items are appropriate for characters of levels 1-4, Rare items are for characters of levels 5-7, and Expert items are appropriate for characters of levels 8-10, but the margin is thin enough that you can get away with going one tier lower or higher.

After you've determined the item's effect, cast the [outcome die](/srd/key-terms#term-outcome-die).  If the result is a 7 or above, the item does not have any enhancements.  If the result is 1-6, the enhancement is shown on the table below:

|Result|Enhancement|
|:-|:-|
|1|All|
|2|Row|
|3|Multi|
|4|Dual|
|5|Delay|
|6|Random|

For the Dual effect, cast the outcome die again for the item's second effect.  Then, if relevant, cast the die on the Random Element Table to determine the elemental type of the item's effect.  If the item is a Buff or Debuff item, use the [Random Statistic Table](/srd/extras/random-tables#term-random-statistic-table) to see what [statistic](/srd/key-terms#term-statistic) it affects.  If the item is a Summon Creature item, choose an enemy from the [Example Enemies](/srd/enemies/examples) section or create one of your own of the appropriate tier.

The last thing to do when creating an item is to calculate its cr value and give it tangible existence in your game world.  It's likely that there is a precedent already for what your players expect certain items to look like, and if so you can just go with that.
