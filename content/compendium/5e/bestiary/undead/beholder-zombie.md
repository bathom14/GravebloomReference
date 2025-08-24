---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/5
- 5e/monster/environment/planar
- 5e/monster/environment/shadowfell
- 5e/monster/environment/underdark
- 5e/monster/environment/urban
- 5e/monster/size/large
- 5e/monster/type/undead
aliases:
- Beholder Zombie
---
# Beholder Zombie
*Source: Monster Manual (2024) p. 347*  

Zombies animated from the corpses of beholders retain some use of those monsters' magical eyestalks. These hovering corpses rely on their magic to destroy impediments and paralyze foes, allowing them to savage foes with their rotting maws.

Magic-using beholders typically raise these abominations from the corpses of defeated rivals.

## Zombies

*Relentless Reanimated Corpses*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Zombies are unthinking, reanimated corpses, often gruesomely marred by decay and lethal traumas. They serve whatever supernatural force animates them—typically evil necromancers or fiendish spirits. Zombies are relentless, merciless, and resilient, and their dead flesh can carry on even after suffering grievous wounds. While they can follow simple orders, they rely on primal drives rather than thought. They fulfill commands by working tirelessly or battering through foes, but they are easily stymied by barriers or unexpected circumstances.

Zombies are usually created from Humanoid corpses, but the remains of other creatures can also become zombies. Such monstrous zombies might possess the strength they had in life or a measure of their supernatural abilities, but they employ such abilities haphazardly at best.

> [!quote] A quote from Account of the Night of the Walking Dead  
> 
> Then, by a spectacular crack of lightning, the figures came into view, moving slowly toward the village. Over driving winds a voice cried out, "The dead come for Marais d'Tarascon! An army of the walking dead!"


## Statblock

```ad-statblock
title: Beholder Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Beholder%20Zombie.webp#token)
*Large undead, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 93 (`11d10 + 33`)
- **Speed** 5 ft., fly 20 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 8 (-1)|16 (+3)| 3 (-4)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [poisoned](rules/5e/conditions.md#Poisoned), [prone](rules/5e/conditions.md#Prone)
- **Languages** understands Deep Speech and Undercommon but can't speak
- **Challenge** 5

## Traits

***Undead Fortitude.*** If damage reduces the zombie to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md), it makes a Constitution saving throw (DC 5 plus the damage taken) unless the damage is Radiant or from a [Critical Hit](rules/5e/variant-rules/critical-hit-xphb.md). On a successful save, the zombie drops to 1 [Hit Point](rules/5e/variant-rules/hit-points-xphb.md) instead.

## Actions

***Multiattack.*** The zombie uses Eye Rays twice.

***Bite.*** *Melee Attack Roll:* `dice:1d20+5|noform|noparens|text(+5)`, reach 5 ft. *Hit:* `dice:4d6+2|noform|noparens|avg|text(16)` (`4d6 + 2`) Piercing damage.

***Eye Rays.*** The zombie randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll `dice:1d4|noform|noparens|avg` (`d4`); reroll if the zombie has already used that ray during this turn):

- **1 Paralyzing Ray.** *Constitution Saving Throw:* DC 14. *Failure:* The target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  
- **2 Fear Ray.** *Wisdom Saving Throw:* DC 14. *Failure:* `dice:3d8|noform|noparens|avg|text(13)` (`3d8`) Psychic damage, and the target has the [Frightened](rules/5e/conditions.md#Frightened) condition until the end of its next turn.  
- **3 Enervation Ray.** *Constitution Saving Throw:* DC 14. *Failure:* `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) Necrotic damage, and the target has the [Poisoned](rules/5e/conditions.md#Poisoned) condition until the end of its next turn. While [Poisoned](rules/5e/conditions.md#Poisoned), the target can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md). *Success:* Half damage only.  
- **4 Disintegration Ray.** *Dexterity Saving Throw:* DC 14. *Failure:* `dice:5d10|noform|noparens|avg|text(27)` (`5d10`) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot [Cube](rules/5e/variant-rules/cube-area-of-effect-xphb.md) of it disintegrates into dust. *Success:* Half damage. *Failure or Success:* If the target is a creature and this damage reduces it to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md), it disintegrates into dust.  
```
^statblock

## Environment

planar, shadowfell, underdark, urban