---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/1
- 5e/monster/size/medium
- 5e/monster/type/humanoid/simic-hybrid
aliases:
- Hybrid Poisoner
---
# Hybrid Poisoner
*Source: Guildmasters' Guide to Ravnica p. 217*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```ad-statblock
title: Hybrid Poisoner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Hybrid%20Poisoner.webp#token)
*Medium humanoid (Simic hybrid), Neutral Good*

- **Armor Class** 14
- **Hit Points** 26 (`4d8 + 8`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|19 (+4)|14 (+2)|12 (+1)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +6, Constitution +4
- **Skills** [Athletics](rules/5e/skills.md#Athletics) +3, [Perception](rules/5e/skills.md#Perception) +3, [Stealth](rules/5e/skills.md#Stealth) +6
- **Senses** darkvision 30 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Common plus any one language
- **Challenge** 1

## Traits

***Assassinate.*** During its first turn, the hybrid poisoner has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the hybrid scores against a [surprised](rules/5e/conditions.md#Surprised) creature is a critical hit.

***Poisonous Skin.*** Any creature that touches the hybrid or hits it with a melee attack while within 5 feet of it takes `dice:1d6|noform|noparens|avg|text(3)` (`d6`) poison damage.

## Actions

***Toxic Touch.*** *Melee Weapon Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6|noform|noparens|avg|text(7)` (`2d6`) bludgeoning damage, and the target must succeed on a DC 12 Constitution saving throw or become [poisoned](rules/5e/conditions.md#Poisoned) for 1 minute. At the end of each of the [poisoned](rules/5e/conditions.md#Poisoned) target's turns, it must repeat the save, taking `dice:1d6|noform|noparens|avg|text(3)` (`d6`) poison damage on a failed save, or ending the effect on itself on a successful one.
```
^statblock