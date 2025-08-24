---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/14
- 5e/monster/environment/underdark
- 5e/monster/size/large
- 5e/monster/type/undead/beholder
aliases:
- Death Tyrant
---
# Death Tyrant
*Source: Monster Manual (2024) p. 95*  

## Death Tyrant

*Beholder beyond Death*

- **Habitat.** Underdark  
- **Treasure.** Any  

A death tyrant is a beholder that pursues aberrant goals beyond its death. Ten magical singularities—all that remains of its magical eyes—orbit its floating, cyclopean skull, while the hateful gaze of its central eye socket stifles life and raises the dead.

Beholders typically transform into death tyrants over years when their dreams fixate on death, morbid apotheoses, or journeys to realms inhospitable to life. Some death tyrants rise from the corpses of slain beholders or result from exposure to strange magic or Underdark radiation. Sometimes beholders purposefully pursue this undead state, just as depraved magic-users pursue lichdom, although it is rare, as most beholders already believe themselves to be perfect beings.

No matter how death tyrants come into being, bizarre impulses drive their deathless existences. Their motivations tend to be extreme or beyond the reason of living creatures.

### Death Tyrant Lairs

Death tyrants often lurk deep in the Underdark, in the tunnel-mazes they occupied in life or in the lairs of enemy beholders they conquered. These lairs are devoid of life, as death tyrants change their servants into Undead horrors.

> [!quote] A quote from Journal of Jastus Hollowquill, explorer of Undermountain  
> 
> A cluster of tiny lights descended from a dark crevice in the ceiling. These motes cast an eerie glow on the great, alien skull that hung beneath them.


```ad-statblock
title: Death Tyrant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Death%20Tyrant.webp#token)
*Large undead (beholder), Lawful Evil*

- **Armor Class** 19
- **Hit Points** 195 (`26d10 + 52`)
- **Speed** 5 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|14 (+2)|19 (+4)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Wisdom +7
- **Skills** [Perception](rules/5e/skills.md#Perception) +12
- **Senses** darkvision 120 ft., passive Perception 22
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned), [prone](rules/5e/conditions.md#Prone)
- **Languages** Deep Speech, Undercommon
- **Challenge** 14

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the death tyrant fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The death tyrant uses Eye Rays three times.

***Bite.*** *Melee Attack Roll:* `dice:1d20+9|noform|noparens|text(+9)`, reach 5 feet. *Hit:* `dice:2d8+4|noform|noparens|avg|text(13)` (`2d8 + 4`) Piercing damage.

***Eye Rays.*** The death tyrant randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll `dice:1d10|noform|noparens|avg` (`d10`); reroll if the death tyrant has already used that ray during this turn):

- **1 Charm Ray.** *Wisdom Saving Throw:* DC 17. *Failure:* `dice:3d8|noform|noparens|avg|text(13)` (`3d8`) Psychic damage, and the target has the [Charmed](rules/5e/conditions.md#Charmed) condition for 1 hour or until it takes damage. *Success:* Half damage only.  
- **2 Paralyzing Ray.** *Constitution Saving Throw:* DC 17. *Failure:* The target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  
- **3 Fear Ray.** *Wisdom Saving Throw:* DC 17. *Failure:* `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) Psychic damage, and the target has the [Frightened](rules/5e/conditions.md#Frightened) condition until the end of its next turn. *Success:* Half damage only.  
- **4 Slowing Ray.** *Constitution Saving Throw:* DC 17. *Failure:* `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) Necrotic damage. Until the end of the target's next turn, the target can't take Reactions; its [Speed](rules/5e/variant-rules/speed-xphb.md) is halved; and it can take either an action or a [Bonus Action](rules/5e/variant-rules/bonus-action-xphb.md) on its turn, not both. *Success:* Half damage only.  
- **5 Enervation Ray.** *Constitution Saving Throw:* DC 17. *Failure:* `dice:3d10|noform|noparens|avg|text(16)` (`3d10`) Poison damage, and the target has the [Poisoned](rules/5e/conditions.md#Poisoned) condition until the end of its next turn. While [Poisoned](rules/5e/conditions.md#Poisoned), the target can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md). *Success:* Half damage only.  
- **6 Telekinetic Ray.** *Strength Saving Throw:* DC 17 (the target succeeds automatically if it is Gargantuan). *Failure:* The death tyrant moves the target up to 30 feet in any direction. The target has the [Restrained](rules/5e/conditions.md#Restrained) condition until the start of the death tyrant's next turn or until the death tyrant has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition. The death tyrant can also exert fine control on objects with this ray, such as manipulating a tool or opening a door or container.  
- **7 Sleep Ray.** *Wisdom Saving Throw:* DC 17 (the target succeeds automatically if it is a Construct or an Undead). *Failure:* The target has the [Unconscious](rules/5e/conditions.md#Unconscious) condition for 1 minute. The condition ends if the target takes damage or a creature within 5 feet of it takes an action to wake it.  
- **8 Petrification Ray.** *Constitution Saving Throw:* DC 17. *1st Failure:* The target has the [Restrained](rules/5e/conditions.md#Restrained) condition and repeats the save at the end of its next turn if it is still [Restrained](rules/5e/conditions.md#Restrained), ending the effect on itself on a success. *2nd Failure:* The target has the [Petrified](rules/5e/conditions.md#Petrified) condition instead of the [Restrained](rules/5e/conditions.md#Restrained) condition.  
- **9 Disintegration Ray.** *Dexterity Saving Throw:* DC 17. *Failure:* `dice:8d8|noform|noparens|avg|text(36)` (`8d8`) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot [Cube](rules/5e/variant-rules/cube-area-of-effect-xphb.md) of it disintegrates into dust. *Success:* Half damage. *Failure or Success:* If the target is a creature and this damage reduces it to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md), it disintegrates into dust.  
- **10 Death Ray.** *Dexterity Saving Throw:* DC 17. *Failure:* `dice:10d10|noform|noparens|avg|text(55)` (`10d10`) Necrotic damage. *Success:* Half damage. *Failure or Success:* The target dies if the ray reduces it to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md).  

## Bonus Actions

***Negative Energy Cone.*** The death tyrant's central eye emits an imperceptible, magical wave of negative energy in a 150-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). Creatures in that area can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) until the start of the death tyrant's next turn. An intact Humanoid corpse there instantly rises as a [Zombie](compendium/5e/bestiary/undead/zombie.md) under the death tyrant's control and takes its turn immediately after the death tyrant on the same initiative count.

## Legendary Actions

***Chomp.*** The death tyrant makes two Bite attacks.

***Glare.*** The death tyrant uses Eye Rays.

![Death Tyrant](compendium/5e/bestiary/legendary-group/death-tyrant.md)
```
^statblock

## Environment

underdark