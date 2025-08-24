---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/3
- 5e/monster/size/medium
- 5e/monster/type/humanoid/any-race
aliases:
- Precognitive Mage
---
# Precognitive Mage
*Source: Guildmasters' Guide to Ravnica p. 228*  

Precognitive mages, a rarity among Azorius spellcasters, are capable of capturing glimpses of the future. They are typically employed to anticipate the actions of wanted criminals, thus aiding in their capture.

```ad-statblock
title: Precognitive Mage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Precognitive%20Mage.webp#token)
*Medium humanoid (any race), Lawful Neutral*

- **Armor Class** 11 (14 with [mage armor](compendium/5e/spells/mage-armor.md))
- **Hit Points** 63 (`14d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|13 (+1)|10 (+0)|18 (+4)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +6, Wisdom +3
- **Skills** [Perception](rules/5e/skills.md#Perception) +3
- **Senses** truesight 120 ft., passive Perception 13
- **Languages** Common plus any one language
- **Challenge** 3

## Traits

***Innate Spellcasting.*** The mage's innate spellcasting ability is Intelligence (spell save DC 14). It can cast the following spells, requiring no material components:

**3/day:** [detect thoughts](compendium/5e/spells/detect-thoughts.md), [mage armor](compendium/5e/spells/mage-armor.md)

**1/day each:** [clairvoyance](compendium/5e/spells/clairvoyance.md), [locate object](compendium/5e/spells/locate-object.md)

## Actions

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+1|noform|noparens|text(+1)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6-1|noform|noparens|avg|text(2)` (`1d6 - 1`) bludgeoning damage, or `dice:1d8-1|noform|noparens|avg|text(3)` (`1d8 - 1`) bludgeoning damage if used with two hands.

***Glimpse the Temporal Flood (Recharge 5-6).*** The mage targets one creature within 120 feet of it that it can see. The target takes `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) psychic damage, and it must succeed on a DC 14 Intelligence saving throw or be [stunned](rules/5e/conditions.md#Stunned) until the end of its next turn.

## Reactions

***Precognitive Insight (3/Day).*** When the mage or a creature it can see makes an attack roll, a saving throw, or an ability check, the mage can cause the roll to be made with advantage or disadvantage.
```
^statblock