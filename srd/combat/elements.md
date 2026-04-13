# The Nine Elements

Heroes, enemies, [eidolons](/srd/heroes/eidolons#term-eidolon), and many [abilities](/srd/glossary#term-ability) all have an extra property called their _<dfn id = "term-element">element</dfn>._  Metaphysically, elements are the forms in which magic is expressed.  There are nine elements in total:
*  <dfn id = "term-fire">Fire</dfn> magic channels the power of heat and flames, and often has a reddish color.
*  <dfn id = "term-water">Water</dfn> magic channels the power of the sea and of storms, and often has a deep blue color.
*  <dfn id = "term-earth">Earth</dfn> magic channels the power of gravity and solid rock, and often has a brownish color.
*  <dfn id = "term-wind">Wind</dfn> magic channel the power of air currents and cyclones, and often has a yellowish-green color.
*  <dfn id = "term-thunder">Thunder</dfn> magic channels the power of electric charge and current, and often has an orange-yellow color.
*  <dfn id = "term-wood">Wood</dfn> magic channels the power of plant life and microorganisms, and often has a dark green color.
*  <dfn id = "term-ice">Ice</dfn> magic channels the power of snow and bitter cold, and often has a light blue color.
*  <dfn id = "term-light">Light</dfn> magic channels the power of radiation and the sun, and often has a whitish color.
*  <dfn id = "term-shadow">Shadow</dfn> magic channels the power of darkness and the unknown, and often has a purple-black color.

An [ability](/srd/glossary#term-ability) or [character](/srd/glossary#term-character) that does not have an element is referred to as _<dfn id = "term-colorless">colorless</dfn>._  Unless they have a [Shell](/srd/combat/shells) active, Heroes count as colorless for the purpose of calculating the damage they take from enemy attacks.

## Elemental Damage

All abilities with an element have their effects modified by the element of the target.  For example, the damage that a [physical](/srd/combat/attacks#term-strike) or [spell](/srd/combat/attacks#term-spell) does is multiplied by an amount determined by both the element of the attack and the element of the target.  Characters with a Shell active will count as having the Shell's element for the purposes of calculating how much damage they receive.  All elements will have as many types they do more damage to and less damage to, but not always to the same degree.  As an example, Wood does 2x damage against Light, Shadow, and Wind, while Fire does 2x damage against Wood and 4x damage against Ice.

## Elemental Multipliers

To determine the damage multiplier for a particular attack, consult the table below by finding the element of the attack listed in the left-hand column and matching it with the element of the target on the top row.  The correct damage multiplier is in the cell at the intersection of the row the attacker's element occupies and the column the defender's element occupies.  If either the attack or the target are colorless, the elemental multiplier is automatically equal to one.  When the resulting damage that a character takes after all multipliers are taken into account is not equal to an integer, round that number down to the nearest integer.  For example, if a character takes 2.5 damage according to the elemental table, this only counts as taking 2 damage in practice.

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
