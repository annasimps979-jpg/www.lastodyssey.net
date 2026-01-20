# Eidolons
A [character's](../Extras/Key-Terms#term-character) _<dfn id="term-eidolon">eidolon</dfn>_ is a demigodlike being whose power protects and is in turn fed by the deepest parts of a character's soul.  Eidolons are extraordinary creatures, and are not necessarily humanlike.  One character might be protected by a powerful dragon, while another might fight alongside an ethereal goddess.  In Last Odyssey, a character's eidolon performs two main functions.  The first of these is to intervene in order to save characters from True Death, and the second of these is to be summoned during combat to fight on their behalf.

A character's summoned eidolon shares their [elemental type](../Combat-Rules/Elemental-Types#term-elemental-type).  The eidolon's elemental type affects the damage that they take in addition to determining the elemental type of their abilities.  An eidolon's [statistics](../Extras/Key-Terms#term-statistic) are determined by the [base](../Extras/Key-Terms#term-base) [attributes](../Extras/Key-Terms#term-attribute) of the character that summoned them and by their eidolon archetype, which is different from the player's.  The exceptions to this are [Mana](../Characters/Attributes-and-Statistics#term-mana), which Eidolons do not need to expend in order to use their abilities, and [Initiative](../Characters/Attributes-and-Statistics#term-initiative), since the Eidolon does not enter the initiative order in the same way as other characters.  Instead, their abilities are either free or cost Anima, and they act during the same turn .  They also have the same number of Action Points that their characters do.  When they are first summoned, they start with the same number of AP that the character who summoned them had remaining before they used the Summon Eidolon [action](../Extras/Key-Terms#term-action), and can immediately take their turn.

At the beginning of each round after an eidolon is summoned, their summoner must either spend 1 Anima to keep them on the field or else the Eidolon stops being summoned and the initiative order goes back to normal.  If the Eidolon drops to 0 [HP](../Characters/Attributes-and-Statistics#term-hp), they are also unsummoned, and will revert back to 1 HP after the [battle](../Extras/Key-Terms#term-battle) is over.  When an Eidolon is unsummoned, whatever HP they had remains until it is healed by their character, but they lose all other effects once the battle is over, including [buffs](../Combat-Rules/Buffs-and-Debuffs#term-buff), [debuffs](../Combat-Rules/Buffs-and-Debuffs#term-debuff), Shells, and status effects.

## Eidolons in Combat
An eidolon's combat statistics are determined by the base attributes of their character.  Their abilities do not cost [MP](../Characters/Attributes-and-Statistics#term-mp).  In addition, eidolons act during their summoner's turn in the initiative order.  Therefore, they do not have Mana or Initiative, but otherwise they share the same statistics that all [player characters](../Extras/Key-Terms#term-player-character) have.  Each of their statistics also receives a bonus given by their archetype, which is the same as the bonus to a player character's statistics from their corresponding [job](../Characters/Jobs/).  For example, an eidolon that is a Striker gets a bonus to their [Physical Attack](../Characters/Attributes-and-Statistics#term-physical-attack) equal to their summoner's [Body](../Characters/Attributes-and-Statistics#term-body), an eidolon that is a Caster gets a bonus to their [Magical Attack](../Characters/Attributes-and-Statistics#term-magical-attack) equal to their summoner's [Mind](../Characters/Attributes-and-Statistics#term-mind), and so on.  The formulae for their statistics are as follows:
*  An eidolon's _[Health](../Characters/Attributes-and-Statistics#term-health)_ is their character's (Body + [Spirit](../Characters/Attributes-and-Statistics#term-spirit) + [Tier](../Characters/Character-Creation#term-tier))x5.
*  An eidolon's _Physical Attack_ is their character's (Body) + (Tier) + (Archetype Bonus).
*  An eidolon's _Magical Attack_ is their character's (Mind) + (Tier) + (Archetype Bonus).
*  An eidolon's _[Physical Defense](../Characters/Attributes-and-Statistics#term-physical-defense)_ is their character's (Body) + (Tier) + (Archetype Bonus).
*  An eidolon's _[Magical Defense](../Characters/Attributes-and-Statistics#term-magical-defense)_ is their character's (Spirit) + (Tier) + (Archetype Bonus).
*  An eidolon's _[Evasion](../Characters/Attributes-and-Statistics#term-evasion)_ is their character's (Mind) + (Tier) + (Archetype Bonus).
*  An eidolon's _[Resistance](../Characters/Attributes-and-Statistics#term-resistance)_ is their character's (Spirit) + (Tier) + (Archetype Bonus).
*  An eidolon's _[Physical Accuracy](../Characters/Attributes-and-Statistics#term-physical-accuracy), [Magical Accuracy](../Characters/Attributes-and-Statistics#term-magical-accuracy),_ and _[Status Accuracy](../Characters/Attributes-and-Statistics#term-status-accuracy)_ are their character's (Mind) + (Body) + (Spirit).

As characters advance in tier, they will unlock unique capstone abilities that only their eidolons can use.  In addition, a character's eidolon may also use two basic abilities and two abilities determined by its archetype.  All eidolons have the following abilities:

|Name|[Type](../Combat-Rules/Attacking-and-Defending#term-ability-type)|Cost|Description|
|:-|:-|:-|:-|
|Attack|[Melee](../Combat-Rules/Attacking-and-Defending#term-melee)|1 AP|Make a [colorless](../Combat-Rules/Elemental-Types#term-colorless) [physical attack](../Combat-Rules/Attacking-and-Defending#term-physical-attack) against a single target.|
|Full Restore|[Self](../Combat-Rules/Attacking-and-Defending#term-self-ability)|1 Anima, 1 AP|The eidolon removes all status effects from itself and immediately restores itself to full HP.|

## Abilities by Archetype

**Striker:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Cleave|[Multi](../Combat-Rules/Attacking-and-Defending#term-multi)|1 AP|Make a colorless physical attack against all enemies in the front row.|
|Elemental Strike|Melee|1 AP|Make a physical attack against a single enemy whose elemental type is the same as the user's elemental type.|

**Caster:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Magic Blast|[Ranged](../Combat-Rules/Attacking-and-Defending#term-ranged)|1 AP|Make a colorless [magical attack](../Combat-Rules/Attacking-and-Defending#term-magical-attack) against a single enemy.|
|Elemental Blast|Ranged|1 AP|Makes a magical attack whose elemental type is the same as the user's elemental type against a single enemy.|

**Healer:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Heal|[Ally](../Combat-Rules/Attacking-and-Defending#term-ally-ability)|1 AP|Heal either the eidolon or a single [party](../Extras/Key-Terms#term-party) member by an amount equal to the eidolon's Magical Attack.  If the ally is [downed](../Characters/Attributes-and-Statistics#term-downed), they are also revived.|
|Cure|Ally|1 AP|Removes all debuffs and status effects from the eidolon or one of the party members.|

**Defender:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Shield|Self|1 AP|The eidolon reflects all physical attacks used against them back at the user as though the user were the target of the attack instead of the eidolon until the beginning of their next turn.  Multi attacks target all enemies.  Attacks that the eidolon has used against itself simply have their damage negated.|
|Barrier|Self|1 AP|The eidolon reflects all magical attacks used against them back at the user as though the user were the target of the attack instead of the eidolon until the beginning of their next turn.  Multi attacks target all enemies.  Attacks that the eidolon has used against itself simply have their damage negated.|

**Support:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Enhance|Ally|1 AP|Bring the [Bonus Tracker](../Combat-Rules/Buffs-and-Debuffs#term-bonus-tracker) of the statistic that the eidolon's summoner's [archetype](../Characters/Archetypes/) buffs to +7 for a single target.  Once the eidolon disappears, all targets of Enhance will be Hasted for three subsequent rounds as though the eidolon has Hasted them on the round it disappeared.|
|Shell|Ally|2 AP|Put the maximum possible Shell of its elemental type on the eidolon or one of its allies.|

**Saboteur:**

|Name|Type|Cost|Description|
|:-|:-|:-|:-|
|Reduce|Ranged|1 AP|Bring the Bonus Tracker of the statistic that their summoner's archetype debuffs to -7 for a single target and apply Slowed as though the eidolon had used the Slow ability on them.|
|Sabotage|Ranged|1 AP|Use a [status-inflicting ability](../Combat-Rules/Attacking-and-Defending#term-status-inflicting-ability) against a single target.  If it succeeds, inflict the status effect associated with their elemental type on the target.|
