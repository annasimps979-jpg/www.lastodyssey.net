# Statuses

A _<dfn id = "term-status">status</dfn>_ is an adjective that sets an extra rule that the [character](/srd/key-terms#term-character) it describes follows while it applies.  In some cases, these create exceptions to existing rules, while in others they add new ones.  For example, a character with the Silenced status may not make spells, while a character with the Slowed status can take fewer [actions](/srd/key-terms#term-action) per [combat round](/srd/combat/round) than normal.  Some [abilities](/srd/key-terms#term-ability) apply statuses automatically, while others are only applied to the target when they are hit.  The latter type are known as [sleights](/srd/combat/attacks#term-sleight).

When a character successfully hits another with a sleight, the target or targets of the ability in question are now under the received status for the duration of the [battle](/srd/key-terms#term-battle), unless they are cured by an item or an ability.  The status inflicted by a sleight is determined by its [element](/srd/combat/elements#term-element).  Unlike damaging abilities, elemental resistances do not change what the ability does on a hit.  Instead, they change the probability that the target will receive the status.  When a character uses a sleight against another character on the battlefield, consult the element table in the [Elements](/srd/combat/elements) section, with the element associated with the power on the left-hand column and the element of the target on the top.  The associated multiplier changes the probability as follows:

|Elemental Multiplier|Equivalent Effect|
|:-|:-|
|0.25x.|  The target is immune to the status.|
|0.5x.|  The status is inflicted when the total die result is 3 or below instead of 5 or below.|
|2x.|  The status is inflicted when the total die result is 7 or below instead of 5 or below.|
|4x.|  The target cannot evade this status.|

## Statuses By Element

Unless otherwise stated, all statuses inflicted by abilities such as the [Artificer's](/srd/heroes/archetypes/artificer) Scan are colorless.  However, there are nine that possess an element, one for each element:

|Element|status|Description|
|:-|:-|:-|
|[Fire](/srd/combat/elements#term-fire)|<dfn id = "term-burned">Burned</dfn>|The affected character cannot receive any healing and cannot be [buffed](/srd/combat/buffs-and-debuffs#term-buff) while this status is active.  Any buffs they have already received remain active until otherwise removed.|
|[Water](/srd/combat/elements#term-water)|<dfn id = "term-confused">Confused</dfn>|When a Confused character uses an ability with a target other than themselves, the [GM](/srd/key-terms#term-gm) flips a coin and has them call heads or tails.  If they call correctly, their ability is used on the intended target.  If they call incorrectly, the GM chooses the target of their ability instead.  If an enemy is Confused, the role of the player and GM are reversed.|
|[Earth](/srd/combat/elements#term-earth)|<dfn id = "term-petrified">Petrified</dfn>|The affected character is unable to use the [Move](/srd/combat/round#term-move) action, and their [base](/srd/key-terms#term-base) [Evasion](/srd/heroes/numbers#term-evasion) counts as being half its current value rounded down, not including buffs and [debuffs](/srd/combat/buffs-and-debuffs#term-debuff).  They may still advance as normal.|
|[Light](/srd/combat/elements#term-light)|<dfn id = "term-blinded">Blinded</dfn>|The affected character's [Physical](/srd/heroes/numbers#term-physical-accuracy), [Magical](/srd/heroes/numbers#term-magical-accuracy), and [Status Accuracy](/srd/heroes/numbers#term-status-accuracy) count as half their values rounded down, not including buffs and debuffs.|
|[Ice](/srd/combat/elements#term-ice)|<dfn id = "term-frostbitten">Frostbitten</dfn>|The affected character is unable to use their [basic attack](/srd/combat/round#term-basic-attack), use items, or use any abilities that restore [Health](/srd/heroes/numbers#term-health) or [Mana](/srd/heroes/numbers#term-mana).  Any abilities they have that heal passively, such as the [Priest's](/srd/heroes/archetypes/priest) Prayer or the Auto Heal equipment power, are not negated by this status.|
|[Wind](/srd/combat/elements#term-wind)|<dfn id = "term-fatigued">Fatigued</dfn>|When the affected character uses an ability that costs [MP](/srd/heroes/numbers#term-mp), the total MP cost they pay to use said ability is doubled.|
|[Thunder](/srd/combat/elements#term-thunder)|<dfn id = "term-paralyzed">Paralyzed</dfn>|Any [strikes](/srd/combat/attacks#term-strike) the character makes automatically miss.  This includes basic attacks or counterattacks due to abilities.|
|[Shadow](/srd/combat/elements#term-shadow)|<dfn id = "term-silenced">Silenced</dfn>|Any [spells](/srd/combat/attacks#term-spell) the character uses automatically miss.  This includes basic attacks or counterattacks due to abilities.|
|[Wood](/srd/combat/elements#term-wood)|<dfn id = "term-poisoned">Poisoned</dfn>|During the [Effect Phase](/srd/combat/round#term-effect-phase) at the end of a round, this character takes damage equal to one tenth of their base maximum [HP](/srd/heroes/numbers#term-hp) rounded down, with a minimum damage of 1.|

## Statuses Outside of Combat

At the end of a battle, most [statuses](/srd/combat/statuses) and all [buffs](/srd/combat/buffs-and-debuffs#term-buff), [debuffs](/srd/combat/buffs-and-debuffs#term-debuff), [Shells](/srd/combat/shells#term-shell), and other effects are removed from all participating characters, with the exception of [Burned](/srd/combat/statuses#term-burned), [Poisoned](/srd/combat/statuses#term-poisoned), and [Frostbitten](/srd/combat/statuses#term-frostbitten), which instead linger in the following ways:
*  Burned: Burned remains after combat, but can be healed if treated by a doctor or the [Mend](/srd/exploration/travel/round#term-mend-action) action.
*  Poisoned: At the end of every [travel round](/srd/exploration/travel/round) during [exploration](/srd/exploration) and every in-game day during [free play](/srd/discovery), Poisoned characters must cast the [outcome die](/srd/key-terms#term-outcome-die) and add their [Resistance](/srd/heroes/numbers#term-resistance) to the result.  If the result is below a 5, they take damage equal to one tenth of their max [HP](/srd/heroes/numbers#term-hp), rounded down, with a minimum damage of 1.  If the result is above a 5, then they stop taking damage from Poisoned.  Poisoned can be healed if treated by a doctor or the Mend action.  If another battle starts before they are cured then they start taking damage every combat [round](/srd/combat/round#term-round) again, and will start taking damage every day again after the battle is over.  The damage done by Poisoned outside of combat cannot ever cause a character to drop below 1 HP.
*  Frostbitten: Frostbitten remains after combat, but can be healed if treated by a doctor or the Mend action.
