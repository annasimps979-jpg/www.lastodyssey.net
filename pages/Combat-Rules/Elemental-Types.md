# Elemental Types

Player characters, enemies, [eidolons](../Characters/Eidolons#term-eidolon), and many [abilities](../Extras/Key-Terms#term-ability) all have an extra property called their _<dfn id = "term-elemental-type">elemental type</dfn>._  Setting wise, you can think of elemental type as the form in which their magic is expressed.  There are nine elemental types:
*  <dfn id = "term-fire">Fire</dfn> magic channels the power of heat and flames, and often has a reddish color.
*  <dfn id = "term-water">Water</dfn> magic channels the power of the sea and of storms, and often has a deep blue color.
*  <dfn id = "term-earth">Earth</dfn> magic channels the power of gravity and solid rock, and often has a brownish color.
*  <dfn id = "term-wind">Wind</dfn> magic channel the power of air currents and cyclones, and often has a yellowish-green color.
*  <dfn id = "term-thunder">Thunder</dfn> magic channels the power of electric charge and current, and often has an orange-yellow color.
*  <dfn id = "term-wood">Wood</dfn> magic channels the power of plant life and microorganisms, and often has a dark green color.
*  <dfn id = "term-ice">Ice</dfn> magic channels the power of snow and bitter cold, and often has a light blue color.
*  <dfn id = "term-light">Light</dfn> magic channels the power of radiation and the sun, and often has a whitish color.
*  <dfn id = "term-shadow">Shadow</dfn> magic channels the power of darkness and the unknown, and often has a purple-black color.

An [ability](../Extras/Key-Terms#term-ability) or [character](../Extras/Key-Terms#term-character) that does not have an elemental type is referred to as _<dfn id = "term-colorless">colorless</dfn>._  Unless they have a [Shell](../Combat-Rules/Shells) active, player characters count as colorless for the purpose of calculating the damage they take from enemy attacks.

All abilities with an elemental type have their effects modified by the elemental type of the target.  For example, the damage that a [physical](../Combat-Rules/Attacking-and-Defending#term-physical-attack) or [magical attack](../Combat-Rules/Attacking-and-Defending#term-magical-attack) does is multiplied by an amount determined by both the elemental type of the attack and the elemental type of the target.  Characters with a Shell active will count as having the Shell's elemental type for the purposes of calculating how much damage they receive.  All elements will have as many types they do more damage to and less damage to, but not always to the same degree.  As an example, Wood does 2x damage against Light, Shadow, and Wind, while Fire does 2x damage against Wood and 4x damage against Ice.

When you are trying to determine the damage multiplier for a particular attack, consult the table below by finding the elemental type of the attack listed in the left-hand column and matching it with the elemental type of the target on the top row.  The correct damage multiplier is in the cell at the intersection of the row the attacker's element occupies and the column the defender's element occupies.  If either the attack or the target are colorless, the elemental multiplier is automatically equal to one.  When the resulting damage that a character takes after all multipliers are taken into account is not equal to an integer, round that number down to the nearest integer.  For example, if a character takes 2.5 damage according to the elemental table, this only counts as taking 2 damage in practice.

|Type    |  Fire   | Water | Earth  |  Wind     |Thunder|  Ice   |  Wood   |  Light   |  Shadow  |
|:-------|:--------|:------|:-------|:----------|:------|:-------|:--------|:---------|:---------|
|  Fire  |    1    |   0.5  |  1    |   0.25    |   1   |    4   |    2    |    1     |    1     |
|  Water |    2    |    1   |  0.5  |     4     |  0.25 |    1   |    1    |    1     |    1     |
|  Earth |    1    |    2   |   1   |    0.5    |   4   |  0.25  |    1    |    1     |    1     |
|  Wind  |    4    |  0.25  |   2   |     2     |   1   |    2   |   0.5   |    4     |   0.25   |
| Thunder|    1    |   4    |  0.25 |     1     |   1   |    2   |    2    |   0.5    |   0.5    |
|  Ice   |   0.25  |   1    |   4   |     2     |  0.5  |    1   |    2    |   0.5    |    1     |
|  Wood  |   0.5   |   1    |   1   |     2     |  0.5  |   0.5  |    1    |    2     |    2     |
|  Light |    1    |    1   |   1   |   0.25    |   2   |    2   |   0.5   |   0.5    |    4     |
| Shadow |    1    |    1   |   1   |    4      |   2   |    1   |   0.5   |   0.25   |    1     |
