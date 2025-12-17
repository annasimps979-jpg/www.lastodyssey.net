---
title: Enemy Creation
---

GMs who want to introduce enemies not included in the Example Enemies section have a few options.  First, they could take a pre-existing enemy and change it superficially, either by altering its creature type or element and the elemental types of its abilities and then changing its name and appearance.  They could also take an existing enemy and change its abilities.  Whatever the GM decides, it is recommended that they not hew too closely to any one roster of "canon" enemies.  This is partially to maintain the sense of danger and discovery for players, and partially because learning about the abilities and statistics of the enemies that player characters will face on the road is a core part of the experience of Last Odyssey.

*  The _creature type_ of an enemy is a single word that best describes the type of living being they are in the context of the setting.  There are a few special items, such as weapons with the Slayer feature, that interact with an enemy's creature type.
*  An enemy's _elemental type_ determines the damage that different elemental attacks do to them, and is explained in more detail in the Elemental Types section.
*  An enemy's _tier_ indirectly determines their combat statistics by setting the number of attribute points available to allocate to determine their statistics.
*  _Aggression_ is a measure of how vicious an enemy is in melee combat, and contributes to an enemy's Physical Attack, Initiative, and Physical Accuracy.
*  _Toughness_ is a measure of how much damage an enemy can take, and contributes to an enemy's Physical Defense, Resistance, and Health.
*  _Magic_ is a measure of how adept an enemy is at dealing with magic, and contributes to an enemy's Magical Attack, Magical Defense, Magical Accuracy, and Mana.
*  _Cunning_ is a measure of how clever and evasive an enemy is, and contributes to an enemy's Evasion, Magical Accuracy, and Status Accuracy, and Initiative.

When creating a new enemy, the GM must spend a fixed amount of points on each of these attributes that depends on the enemy's tier.  At tier 1, Normal enemies have 6 points to distribute, Elite enemies have 8, and a Phase of an Antagonist has 10.  Each additional tier grants 2 more points to Normal enemies, 3 more points to Elite enemies, and 4 more points to Antagonists.  The minimum value that an enemy can have in each of their attributes is 0.  The maximum value that a Normal enemy can have in a given attribute is 10, the maximum value an Elite can have is 15, and the maximum that an Antagonist can have is 20.  In addition to attribute points, the Health, Mana, and Initiative of all enemies are adjusted by a number called the enemy's _tier multiplier._  The tier multipliers for a Normal enemy are 5 for their Health and Mana and 1 for their Initiative, Elites have multipliers of 10 for their Health and Mana and 2 for their Initiative, and Antagonists have 20 for their Health and Mana and 2 for their Initiative.

Once attribute points have been allocated, the enemy's combat statistics are determined by their attributes by the following formulae:
*  Health = (Toughness)x5 + (Tier)x(Tier Multiplier).
*  Mana = (Magic)x5 + (Tier)x(Tier Multiplier).
*  Initiative = (Aggression) + (Cunning) + (Tier)x(Tier Multiplier).
*  Physical Attack = (Aggression)x2.
*  Magical Attack = (Magic)x2.
*  Physical Defense = (Toughness).
*  Magical Defense = (Magic).
*  Evasion = (Cunning)x2.
*  Resistance = (Toughness)x2.
*  Physical Accuracy = (Aggression)x2.
*  Magical Accuracy = (Cunning) + (Magic).
*  Status Accuracy = (Cunning)x2.

Unlike player characters, enemies' maximum HP and Shell are distinct values.  The total combined HP plus Shell of a single enemy is equal to its Health, and the ratio of its HP to its Shell is equal to the ratio of its Toughness plus its Aggression to its Magic plus its Cunning.  For example, an enemy with an Aggression of 4, a Toughness of 5, a Magic of 3, and a Cunning of 3 would have HP equal to three fifths of its Health and Shell equal to two fifths of its Health.  If the value calculated isn't exact (and it often won't be) just round to the nearest integer.  Once statistics are calculated, the GM can then adjust them if they like.  When doing so, they should remember that 1 point of Physical or Magical Defense is worth 2 points of Physical Attack, Magical Attack, Evasion, Resistance, Physical Accuracy, Magical Accuracy, or Status Accuracy, and also worth 5 points of Health or Mana.

After setting the combat statistics of an enemy, the GM should then choose its abilities.  Normal enemies should get two abilities, and Elite enemies should get four.  If the enemy does not have a basic attack, they receive an extra ability.  All of an enemy's abilities should be drawn from the lists of abilities for character jobs and classes and from the abilities of all other enemies in the Example Enemies section of their tier or below.  In the case of character abilities, enemies can only have access to abilities associated with a rank of a class or job equal to twice their tier.  In addition to active abilities, enemies may also have passive abilities, which are extra effects that activate when certain conditions are met.  For example, an enemy might have an ability that makes them immune to water damage, or might gain the Focused status effect when they lose their Shell.  GMs are encouraged to come up with passives on their own, and should use the passive abilities of the enemies in the Example Enemies section as guidelines for how to do this.

After an enemy's combat statistics and abilities have been determined, they are technically ready to be deployed into a campaign.  However, GMs should remember that an enemy is a living entity that makes decisions based on imperatives other than battle tactics.  The last thing they do, then, should be to determine the enemy's behavior.  At minimum, GMs should note down what other enemies they will fight alongside, if any, and what pattern of abilities they will use in combat.  For example, an enemy that is mindless and aggressive might attack any of their opponents in the front row at random, while a group of enemies using squadron tactics will rotate out who is in the front row based on their remaining HP and Shell.  Once this is done, the enemy has been created.

In total, GMs creating a new enemy should complete the following steps:
1.  Determine its tier and whether it is Normal, Elite, or an Antagonist.
2.  Determine its creature type.'
3.  Determine its elemental type.
4.  Determine its attributes.
5.  Assign combat statistics based on the values of its attributes, and adjust as needed.
6.  Determine its abilities.
7.  Determine its behavior in and out of combat.
