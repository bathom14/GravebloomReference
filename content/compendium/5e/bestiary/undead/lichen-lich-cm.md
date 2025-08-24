---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/cm
- 5e/monster/cr/18
- 5e/monster/size/medium
- 5e/monster/type/undead
aliases:
- Lichen Lich
---
# Lichen Lich
*Source: Candlekeep Mysteries p. 223*  

Lichen liches are undead remnants of powerful druids.

A lichen lich looks like a skeleton covered with fungi and bark-like lichen. A lichen lich has vines within its chest cavity. These vines exude viscid and poisonous black fluid.

```ad-statblock
title: Lichen Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Lichen%20Lich.webp#token)
*Medium undead, Unaligned*

- **Armor Class** 20 (natural armor)
- **Hit Points** 225 (`30d8 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|14 (+2)|20 (+5)|16 (+3)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +9, Intelligence +8, Wisdom +11, Charisma +9
- **Skills** [Medicine](rules/5e/skills.md#Medicine) +11, [Nature](rules/5e/skills.md#Nature) +14, [Perception](rules/5e/skills.md#Perception) +11, [Survival](rules/5e/skills.md#Survival) +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** cold, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned), [stunned](rules/5e/conditions.md#Stunned)
- **Languages** Common, Druidic, Sylvan
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the lich fails a saving throw, it can choose to succeed instead.

***Rejuvenation.*** If it has a phylactery, a destroyed lich gains a new body in `dice:1d10|noform|noparens|avg` (`d10`) days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.

## Actions

***Multiattack.*** The lich makes four attacks.

***Poisonous Touch.*** *Melee Weapon Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 10 ft., one creature. *Hit:* `dice:5d6|noform|noparens|avg|text(17)` (`5d6`) poison damage, and the target must succeed on a DC 19 Constitution saving throw or be [poisoned](rules/5e/conditions.md#Poisoned) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Wither.*** *Ranged Spell Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) necrotic damage.

***Fire Storm (7th-Level Spell; 1/Day).*** The lich fills up to ten 10-foot cubes with fire. Every cube must be within 150 feet of the lich and occupy a space the lich can see, and each cube must have at least one face adjacent to the face of another cube. Each creature in the area must make a DC 19 Dexterity saving throw, taking `dice:7d10|noform|noparens|avg|text(38)` (`7d10`) fire damage on a failed save, or half as much damage on a successful one. The fire ignites flammable objects in the area that aren't being worn or carried. If the lich chooses, plant life in the area is unaffected by the spell.

***Spellcasting.*** The lich casts one of the following spells using Wisdom as the spellcasting ability (save DC 19):

**At will:** [druidcraft](compendium/5e/spells/druidcraft.md)

**3/day each:** [detect magic](compendium/5e/spells/detect-magic.md), [fog cloud](compendium/5e/spells/fog-cloud.md), [pass without trace](compendium/5e/spells/pass-without-trace.md)

**1/day each:** [antilife shell](compendium/5e/spells/antilife-shell.md), [dispel magic](compendium/5e/spells/dispel-magic.md), [speak with plants](compendium/5e/spells/speak-with-plants.md), [transport via plants](compendium/5e/spells/transport-via-plants.md)

## Legendary Actions

***Attack.*** The lich makes an attack.

***Poison Prick (Cost 2 Actions).*** The lich targets one [poisoned](rules/5e/conditions.md#Poisoned) creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or fall [unconscious](rules/5e/conditions.md#Unconscious) until the [poisoned](rules/5e/conditions.md#Poisoned) condition ends on it.

***Sap Life (Costs 2 Actions).*** The lich targets one creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or take `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) necrotic damage. The lich regains a number of hit points equal to the amount of damage that the creature takes.

![Lichen Lich](compendium/5e/bestiary/legendary-group/lichen-lich-cm.md)
```
^statblock