# Status Effects

A _<dfn id = "term-status-effect">status effect</dfn>_ is an adjective that sets an extra rule that the [character](../Extras/Key-Terms#term-character) it describes follows while it applies.  In some cases, these create exceptions to existing rules, while in others they add new ones.  For example, a character with the Silenced status effect may not make magical attacks, while a character with the Slowed status effect can take fewer [actions](../Extras/Key-Terms#term-action) per combat round than normal.  Some [abilities](../Extras/Key-Terms#term-ability) apply status effects automatically, while others are only applied to the target with a successful roll of the hit die.  The latter type are known as status-inflicting abilities.

When a character successfully hits another with a status-inflicting ability, the target or targets of the ability in question are now under the received status effect for the duration of the [battle](../Extras/Key-Terms#term-battle), unless they are cured by an item or an ability.  The status effect inflicted by a status-inflicting ability is determined by its elemental type.  Unlike damaging abilities, elemental resistances do not change what the ability does on a hit.  Instead, they change the probability that the target will receive the status effect.  When a character uses a status-inflicting ability against another character on the battlefield, consult the element table in the [Elemental Types](../Combat-Rules/Elemental-Types) section, with the element associated with the power on the left-hand column and the element of the target on the top.  There is no such thing as a colorless status effect.  The associated multiplier changes the probability as follows:

|Elemental Multiplier|Equivalent Effect|
|:-|:-|
|0.25x.|  The target is immune to the status effect.|
|0.5x.|  The status effect is inflicted when the result of the status-inflicting ability roll is 3 or below instead of 5 or below.|
|2x.|  The status effect is inflicted when the result of the status-inflicting ability roll is 7 or below instead of 5 or below.|
|4x.|  The target cannot evade this status effect.|

There are nine basic negative status effects that [player](../Extras/Key-Terms#term-player) abilities can inflict, one for each elemental type:
*  Fire: <dfn id = "term-burned">Burned</dfn>.  The affected character cannot receive any healing and cannot be buffed while this status is active.  Any buffs they have already received remain active until otherwise removed.
*  Water: <dfn id = "term-confused">Confused</dfn>.  When a Confused character uses an ability with a target other than themselves, the [GM](../Extras/Key-Terms#term-gm) flips a coin and has them call heads or tails.  If they call correctly, their ability is used on the intended target.  If they call incorrectly, the GM chooses the target of their ability instead.  If an enemy is Confused, the role of the player and GM are reversed.
*  Earth: <dfn id = "term-petrified">Petrified</dfn>.  The affected character is unable to use the Move action, and their [base](../Extras/Key-Terms#term-base) Evasion counts as being half its current value rounded down, not including buffs and debuffs.  They may still advance as normal.
*  Light: <dfn id = "term-blinded">Blinded</dfn>.  The affected character's Physical, Magical, and Status Accuracy count as half their values rounded down, including buffs and debuffs.
*  Ice: <dfn id = "term-frostbitten">Frostbitten</dfn>.  The affected character is unable to use their basic attack, use items, or use any abilities that restore Health or Mana.  Any abilities they have that heal passively, such as the Priest's Prayer or the Auto Heal equipment power, are not negated by this status effect.
*  Wind: <dfn id = "term-fatigued">Fatigued</dfn>.  When the affected character uses an ability that costs MP, the total MP cost they pay to use said ability is doubled.
*  Thunder: <dfn id = "term-paralyzed">Paralyzed</dfn>.  Any physical attacks the character makes automatically miss.  This includes basic attacks or counterattacks due to abilities.
*  Shadow: <dfn id = "term-silenced">Silenced</dfn>.  Any magical attacks the character makes automatically miss.  This includes basic attacks or counterattacks due to abilities.
*  Wood: <dfn id = "term-poisoned">Poisoned</dfn>.  During the Effect Phase at the end of a round, this character takes damage equal to one tenth of their base maximum HP rounded down, with a minimum damage of 1.
