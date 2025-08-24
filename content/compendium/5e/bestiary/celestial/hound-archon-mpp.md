---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpp
- 5e/monster/cr/4
- 5e/monster/size/medium
- 5e/monster/type/celestial
aliases:
- Hound Archon
---
# Hound Archon
*Source: Morte's Planar Parade p. 16*  

Hound archons are the foot soldiers of Mount Celestia, tasked with protecting the innocent and helpless. Loyal defenders, these bipedal warriors wield blades of shining radiance and can assume canine forms, allowing them to inconspicuously guard peaceable communities as dogs and wolves.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

## Statblock

```ad-statblock
title: Hound Archon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Hound%20Archon.webp#token)
*Medium celestial, typically  Lawful Good*

- **Armor Class** 15 (natural armor)
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|15 (+2)|11 (+0)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +2, Wisdom +4
- **Skills** [Insight](rules/5e/skills.md#Insight) +4, [Perception](rules/5e/skills.md#Perception) +6, [Stealth](rules/5e/skills.md#Stealth) +3
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Immunities** lightning
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [paralyzed](rules/5e/conditions.md#Paralyzed)
- **Languages** all
- **Challenge** 4

## Traits

***Aura of Menace.*** As long as the archon doesn't have the [incapacitated](rules/5e/conditions.md#Incapacitated) condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 12 Wisdom saving throw. On a failed save, the creature has the [frightened](rules/5e/conditions.md#Frightened) condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.

## Actions

***Multiattack.*** The archon makes two Bite attacks. It can replace one of the attacks with a Shining Blade attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|noparens|avg|text(7)` (`1d6 + 4`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Strength saving throw or have the [prone](rules/5e/conditions.md#Prone) condition.

***Shining Blade (True Form Only).*** *Melee Weapon Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|noparens|avg|text(11)` (`2d6 + 4`) radiant damage.

***Teleport.*** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.

***Spellcasting.*** The archon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability:

**At will:** [detect evil and good](compendium/5e/spells/detect-evil-and-good.md)

**1/day each:** [aid](compendium/5e/spells/aid.md), [continual flame](compendium/5e/spells/continual-flame.md)

## Bonus Actions

***Change Shape.*** The archon magically transforms into any Medium or Large dog or wolf while retaining its game statistics (other than its size and losing its Shining Blade attack). The archon reverts to its true form if reduced to 0 hit points or if it uses a bonus action to do so.
```
^statblock