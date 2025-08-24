---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/8
- 5e/monster/environment/any
- 5e/monster/size/small-or-medium
- 5e/monster/type/humanoid
aliases:
- Assassin
---
# Assassin
*Source: Monster Manual (2024) p. 22, Dragon Delves. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Assassin

*Contract Killer*

- **Habitat.** Any  
- **Treasure.** Implements, Individual  

Assassins are professional killers skilled at stealthily approaching their victims and striking unseen. Most assassins kill for a reason, perhaps hiring themselves out to wealthy patrons or slaying for an unscrupulous cause. They use poisons and other deadly tools, and they might carry equipment to help them break into secure areas or avoid capture.

Many assassins adhere to a professional code or exhibit some signature quirk. Roll on or choose a result from the Assassin Modus Operandi table to inspire an assassin's distinctive habits.

**Assassin Modus Operandi**

`dice: [](assassin.md#^assassin-modus-operandi)`

| dice: 1d6 | The Assassin Is Infamous For... |
|-----------|---------------------------------|
| 1 | Arranging their victims in artful tableaux. |
| 2 | Hiding within large objects, such as suits of armor or hollow furnishings. |
| 3 | Leaving behind a signature item, such as a calling card, flower, seashell, or tooth. |
| 4 | Posing as celebrities, holy people, or servants. |
| 5 | Taking trophies from their victims. |
| 6 | Using poison with a distinctive color or smell. |
^assassin-modus-operandi

```ad-statblock
title: Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Assassin.webp#token)
*Small or Medium humanoid, Neutral*

- **Armor Class** 16
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|14 (+2)|16 (+3)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Intelligence +6
- **Skills** [Acrobatics](rules/5e/skills.md#Acrobatics) +7, [Perception](rules/5e/skills.md#Perception) +6, [Stealth](rules/5e/skills.md#Stealth) +10
- **Senses** passive Perception 16
- **Damage Resistances** poison
- **Languages** Common, Thieves' cant
- **Challenge** 8

## Traits

***Evasion.*** If the assassin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the assassin instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** The assassin makes three attacks, using Shortsword or Light Crossbow in any combination.

***Shortsword.*** *Melee Attack Roll:* `dice:1d20+7|noform|noparens|text(+7)`, reach 5 ft. *Hit:* `dice:1d6+4|noform|noparens|avg|text(7)` (`1d6 + 4`) Piercing damage plus `dice:5d6|noform|noparens|avg|text(17)` (`5d6`) Poison damage, and the target has the [Poisoned](rules/5e/conditions.md#Poisoned) condition until the start of the assassin's next turn.

***Light Crossbow.*** *Ranged Attack Roll:* `dice:1d20+7|noform|noparens|text(+7)`, range 80/320 ft. *Hit:* `dice:1d8+4|noform|noparens|avg|text(8)` (`1d8 + 4`) Piercing damage plus `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) Poison damage.

## Bonus Actions

***Cunning Action.*** The assassin takes the Dash, Disengage, or Hide action.
```
^statblock

## Environment

any