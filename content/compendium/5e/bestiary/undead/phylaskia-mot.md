---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mot
- 5e/monster/cr/9
- 5e/monster/size/large
- 5e/monster/type/undead
aliases:
- Phylaskia
---
# Phylaskia
*Source: Mythic Odysseys of Theros p. 239*  

These armored skeletal spirits guard the borders of the Underworld and its various wards. Sleepless and merciless, they scrutinize all who would pass, and they slay those who defy them.

```ad-statblock
title: Phylaskia
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Phylaskia.webp#token)
*Large undead, Lawful Neutral*

- **Armor Class** 18 ([plate](compendium/5e/items/plate-armor-phb.md))
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|18 (+4)|10 (+0)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** [Insight](rules/5e/skills.md#Insight) +7, [Perception](rules/5e/skills.md#Perception) +7
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [blinded](rules/5e/conditions.md#Blinded), [charmed](rules/5e/conditions.md#Charmed), [deafened](rules/5e/conditions.md#Deafened), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** all
- **Challenge** 9

## Traits

***Gatekeeper's Aura.*** Any creature that starts its turn within 10 feet of the phylaskia must make a DC 15 Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage on saving throws and its speed is halved until the start of its next turn.

***Undead Fortitude.*** If damage reduces the phylaskia to 0 hit points, it must make a Constitution saving throw with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the phylaskia drops to 1 hit point instead.

***Vigilant.*** The phylaskia can't be [surprised](rules/5e/conditions.md#Surprised).

## Actions

***Multiattack.*** The phylaskia makes two longsword attacks and uses its Strength Drain once.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+5|noform|noparens|avg|text(14)` (`2d8 + 5`) slashing damage, or `dice:2d10+5|noform|noparens|avg|text(16)` (`2d10 + 5`) slashing damage if used with two hands, plus `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) necrotic damage.

***Strength Drain.*** *Melee Weapon Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+5|noform|noparens|avg|text(12)` (`2d6 + 5`) necrotic damage. Unless the target is immune to necrotic damage, its Strength score is reduced by `dice:1d4|noform|noparens|avg` (`d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.
```
^statblock