# Attacks

Some [character](/srd/key-terms#term-character) [abilities](/srd/key-terms#term-ability), such as [buffs](/srd/combat/buffs-and-debuffs#term-buff) and [debuffs](/srd/combat/buffs-and-debuffs#term-debuff), succeed no matter what.  However, some offensive abilities that can hit or miss depending on the circumstances.  These abilities are referred to as _<dfn id = "term-attack">attacks.</dfn>_  There are three types of attacks: strikes, spells, and sleights.  The same mechanics listed below for [Heroes](/srd/key-terms#term-hero) and their allies targeting enemies also apply to enemies targeting Heroes or their allies.  When a character uses any of these three kinds of abilities, the [outcome die](/srd/key-terms#term-outcome-die) is known as the _<dfn id="term-hit-die">hit die</dfn>,_ and will determine whether or not the ability succeeds.  If the ability in question targets multiple enemies, the hit die is only cast once, and the resulting number determines whether they hit and the [base](/srd/key-terms#term-base) damage they deal against each one separately.

## Strikes
When a character makes a _<dfn id="term-strike">strike</dfn>_ against an enemy or enemies, cast the hit die, subtract their [Physical Accuracy](/srd/heroes/attributes-and-statistics#term-physical-accuracy) from the result, and then add their opponent's [Evasion](/srd/heroes/attributes-and-statistics#term-evasion).  If the resulting number is equal to a 7 or below, the character hits and deals damage that reduces the target's total [HP](/srd/heroes/attributes-and-statistics#term-hp).  Otherwise, they miss and deal no damage.  The base damage of the attack is equal to the attacker's [Physical Attack](/srd/heroes/attributes-and-statistics#term-strike) minus the enemy's [Physical Defense](/srd/heroes/attributes-and-statistics#term-physical-defense) plus the result of the hit die multiplied by any relevant damage modifiers.

## Spells
When a character uses a _<dfn id="term-spell">spell</dfn>_ against an enemy or enemies, cast the hit die, subtract their [Magical Accuracy](/srd/heroes/attributes-and-statistics#term-magical-accuracy) from the result, and then add their opponent's Evasion.  If the resulting number is equal to a 7 or below, they hit and deal damage that reduces the target's total HP.  Otherwise, they miss and deal no damage.  The base damage of the attack is equal to the attacker's [Magical Attack](/srd/heroes/attributes-and-statistics#term-spell) minus the enemy's [Magical Defense](/srd/heroes/attributes-and-statistics#term-magical-defense) plus the result of the hit die multiplied by any relevant damage modifiers.

## Sleights
When a character uses a _<dfn id="term-sleight">sleight</dfn>_ on an enemy, cast the hit die and subtract their [Status Accuracy](/srd/heroes/attributes-and-statistics#term-status-accuracy) from the result.  To determine whether or not each enemy is hit, add their [Resistance](/srd/heroes/attributes-and-statistics#term-resistance) to the result.  If the result is equal to or below a 5, they gain the [status](/srd/combat/statuses) the ability inflicts.

## Ability Types

Every ability has an <dfn id = "term-ability-type">ability type</dfn> that specifies its target.  They are as follows:

|Type|Description|
|:-|:-|
|<dfn id = "term-self-ability">Self</dfn>|This ability may only target the user.|
|<dfn id = "term-melee">Melee</dfn>|This ability may only be used when the user is in the [front row](/srd/combat/starting#term-front-row), and may only target characters that are in the front row.|
|<dfn id = "term-ranged">Ranged</dfn>|This ability is offensive, and may target any character on the battlefield.|
|<dfn id = "term-ally-ability">Ally</dfn>|This ability is defensive, and may target any character on the battlefield.|
|<dfn id = "term-special-ability">Special</dfn>|The possible targets of this ability are contextual.  Read its description to learn when it can be used.|
|<dfn id = "term-passive">Passive</dfn>|This ability cannot be used as an [action](/srd/key-terms#term-action), but instead changes something about the way the character behaves in [combat](/srd/combat).|
|<dfn id = "term-multi">Multi</dfn>|This ability targets more than one character on the battlefield.|
|<dfn id = "term-reaction">Reaction</dfn>|This ability cannot be used as an action, but triggers automatically when certain conditions are met.|

## General Notes

Sometimes, the total Evasion or Resistance of the target of an ability is great enough that there is no chance that the ability will hit them.  For status-inflicting abilities, this means that they cannot be hit.  For magical and physical, attacks, however, a result of 1 will still lead to a hit.  If the resulting damage would be 0, it is still 0.

The minimum amount of base damage a character deals with an attack is 1.  However, the base damage they deal is not equal to the final damage the enemy takes.  Instead, the final damage they take is equal to the base damage of the attack multiplied by any relevant modifiers and then rounded to the nearest integer.  When a [character](/srd/key-terms#term-character) makes a spell against an opponent that has a Shell active, they do double damage.  Likewise, when a character makes a strike against an opponent that does not have a Shell active, they also do double damage.

## Multi Attacks

Some abilities, such as Cleave or Elemental Storm, will target multiple characters at once.  When a character makes one of these attacks, their player only casts the hit die once and subtracts the corresponding accuracy bonus from it.  However, to determine whether or not they hit each enemy and whether or not they deal damage if applicable, add each enemy's Evasion or Resistance to the result individually to determine whether or not each enemy is hit.  For example, let's say a character has a Physical Accuracy of 3 and a Physical Attack of 2.  They attack two enemies, and receive a 5 on the outcome die, meaning that their accuracy result is a 2 and their damage result is a 7.  The first enemy has an Evasion of 6 and a Physical Defense of 1, so the attack misses them.  The second enemy has an Evasion of 2 and a Physical Defense of 3, so the attack hits them with a base damage of 4.

## Leaning In

Sometimes, players may wish to attack allies instead of their enemies.  If so, the rule of thumb is that an ability used on the opposite side of the battlefield as intended works as though its user occupies the opposite side they currently do.  For example, if a Hero uses an Ally ability on an enemy, it works as though that enemy were instead their ally.  If the ability in question is a strike, spell, or sleight, the target of the ability may choose to be hit even if the result on the hit die means that the ability ought to miss.  When brought up elsewhere in the rules, this is referred to as _<dfn id = "term-lean-in">leaning in.</dfn>_  Characters may also choose to lean into an ability used by one of their enemies if they wish.

## Nonlethal Attacks

Instead of doing lethal damage, [players](/srd/key-terms#term-player) may instead choose to nonlethally _<dfn id = "term-knock-out">knock out</dfn>_ their opponents.  To do so, a Hero must declare that they are executing an attack meant to knock an enemy out rather than kill.  The damage of the attack, if it hits, is calculated as though they had received a 1 on the hit die.  If the enemy is [downed](/srd/heroes/attributes-and-statistics#term-downed), they will be temporarily incapacitated instead of killed.
