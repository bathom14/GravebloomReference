---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpp
- 5e/monster/cr/10
- 5e/monster/size/large
- 5e/monster/type/fiend
aliases:
- Maelephant
---
# Maelephant
*Source: Morte's Planar Parade p. 35, Sigil and the Outlands*  

Respected as guardians by villains across the multiverse, maelephants are Fiends with pachyderm-like heads. They can exhale toxic fumes that cause foes to temporarily forget their combat training, spellcasting abilities, and other skills.

Maelephants strike bargains with wicked spellcasters and entities of the Lower Planes, pledging to guard a site or object for decades. The Fiends fulfill their end of the bargain with unwavering loyalty, steadfastly tending to their posts per the terms of their agreement.

```ad-statblock
title: Maelephant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Maelephant.webp#token)
*Large fiend, typically  Lawful Evil*

- **Armor Class** 15 ([half plate armor](compendium/5e/items/half-plate-armor-phb.md))
- **Hit Points** 161 (`17d10 + 68`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|10 (+0)|18 (+4)|10 (+0)|16 (+3)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +8, Constitution +8
- **Skills** [Perception](rules/5e/skills.md#Perception) +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** acid, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [frightened](rules/5e/conditions.md#Frightened), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Infernal
- **Challenge** 10

## Traits

***Magic Resistance.*** The maelephant has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The maelephant makes one Barbed Trunk attack and two Glaive attacks.

***Barbed Trunk.*** *Melee Weapon Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|noparens|avg|text(13)` (`2d8 + 4`) piercing damage plus `dice:2d12|noform|noparens|avg|text(13)` (`2d12`) poison damage. If the target is a Medium or smaller creature, it has the [grappled](rules/5e/conditions.md#Grappled) condition (escape DC 14). Until this grapple ends, the target has the [restrained](rules/5e/conditions.md#Restrained) condition. While it is grappling a creature, the maelephant can't use its barbed trunk to attack other creatures.

***Glaive.*** *Melee Weapon Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+4|noform|noparens|avg|text(15)` (`2d10 + 4`) slashing damage.

***Mind Poison (Recharge 5-6).*** The maelephant expels poisonous gas from its trunk in a 60-foot cone. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes `dice:6d12|noform|noparens|avg|text(39)` (`6d12`) poison damage and has the [poisoned](rules/5e/conditions.md#Poisoned) condition. While [poisoned](rules/5e/conditions.md#Poisoned) in this way, the creature loses all weapon and skill proficiencies, it can't cast spells, it can't understand language, and it has disadvantage on Intelligence saving throws. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, the target takes half as much damage only and is immune to this maelephant's Mind Poison for 24 hours.
```
^statblock