---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpp
- 5e/monster/cr/5
- 5e/monster/size/small-or-medium
- 5e/monster/type/humanoid
aliases:
- Fated Shaker
---
# Fated Shaker
*Source: Morte's Planar Parade p. 56, Sigil and the Outlands*  

Fated shakers are bullies who shake down those indebted to the faction's tax collectors and evictors. These enforcers use their magic to intimidate and subjugate those who try to stand up to them.

```ad-statblock
title: Fated Shaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Fated%20Shaker.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 13 (16 with [mage armor](compendium/5e/spells/mage-armor.md))
- **Hit Points** 76 (`17d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|10 (+0)|15 (+2)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +5, Wisdom +6
- **Skills** [Insight](rules/5e/skills.md#Insight) +6, [Investigation](rules/5e/skills.md#Investigation) +5, [Perception](rules/5e/skills.md#Perception) +6
- **Senses** passive Perception 16
- **Languages** Common plus two more languages
- **Challenge** 5

## Actions

***Multiattack.*** The shaker makes two Golden Rod or Radiant Bolt attacks.

***Golden Rod.*** *Melee Weapon Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|noparens|avg|text(6)` (`1d6 + 3`) bludgeoning damage plus `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) radiant damage.

***Radiant Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, range 120 ft., one target. *Hit:* `dice:2d10+3|noform|noparens|avg|text(14)` (`2d10 + 3`) radiant damage.

***Spellcasting.*** The shaker casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 14):

**At will:** [mage armor](compendium/5e/spells/mage-armor.md), [mage hand](compendium/5e/spells/mage-hand.md)

**1/day each:** [enlarge/reduce](compendium/5e/spells/enlarge-reduce.md), [fly](compendium/5e/spells/fly.md), [suggestion](compendium/5e/spells/suggestion.md)

## Bonus Actions

***Commanding Words.*** The shaker speaks magical words to order a creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be affected by one of the following effects (choose one or roll a `dice:d4|noform|noparens|avg` (`d4`)):

- **1-2 Grovel.** The target takes `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) psychic damage, drops whatever it is holding, and has the [prone](rules/5e/conditions.md#Prone) condition.  
- **3-4 Cower.** The target takes `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) psychic damage and has the [frightened](rules/5e/conditions.md#Frightened) condition until the end of its next turn.  
```
^statblock