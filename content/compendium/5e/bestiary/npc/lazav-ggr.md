---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/17
- 5e/monster/size/medium
- 5e/monster/type/monstrosity/shapechanger
aliases:
- Lazav
---
# Lazav
*Source: Guildmasters' Guide to Ravnica p. 232*  

Lazav is uniquely qualified to be the Dimir guildmaster: he is a shapechanger whose mysterious genius is informed by agents from the entire Dimir network. He takes on a tremendous variety of guises as his needs and plans require. He might step out into the Ravnican streets as an elderly widow to eavesdrop at the bazaar, become a vedalken hussar of the Azorius Senate to sidestep a checkpoint, or transform into a Tin Street merchant to deceive a passing noble. His true form might be that of a doppelganger or some other creature; no one has ever seen it.

```ad-statblock
title: Lazav
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Lazav.webp#token)
*Medium monstrosity (shapechanger), Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 204 (`24d8 + 96`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|24 (+7)|18 (+4)|22 (+6)|20 (+5)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +13, Intelligence +12, Wisdom +11, Charisma +12
- **Skills** [Deception](rules/5e/skills.md#Deception) +18, [Insight](rules/5e/skills.md#Insight) +11, [Perception](rules/5e/skills.md#Perception) +11, [Stealth](rules/5e/skills.md#Stealth) +19
- **Senses** darkvision 120 ft., passive Perception 21
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [frightened](rules/5e/conditions.md#Frightened), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Common, Thieves' cant
- **Challenge** 17

## Traits

***Innate Spellcasting.*** Lazav's innate spellcasting ability is Intelligence (spell save DC 20). He can innately cast the following spells, requiring no material components:

**At will:** [detect thoughts](compendium/5e/spells/detect-thoughts.md), [encode thoughts](compendium/5e/spells/encode-thoughts-ggr.md) (see chapter 2), [freedom of movement](compendium/5e/spells/freedom-of-movement.md), [vicious mockery](compendium/5e/spells/vicious-mockery.md) (`dice:4d4|noform|noparens|avg` (`4d4`) psychic damage)

**3/day each:** [blur](compendium/5e/spells/blur.md), [confusion](compendium/5e/spells/confusion.md), [mirror image](compendium/5e/spells/mirror-image.md)

**1/day each:** [modify memory](compendium/5e/spells/modify-memory.md), [Rary's telepathic bond](compendium/5e/spells/rarys-telepathic-bond.md)

***Elusive.*** No attack roll has advantage against Lazav unless he is [incapacitated](rules/5e/conditions.md#Incapacitated).

***Legendary Resistance (3/Day).*** If Lazav fails a saving throw, he can choose to succeed instead.

***Shapechanger Savant.*** Lazav can use a bonus action to polymorph into a Small or Medium humanoid he has seen. His statistics, other than his size, are the same in each form. Any equipment he is wearing or carrying isn't transformed.

***Psychic Defenses.*** Unless Lazav is [incapacitated](rules/5e/conditions.md#Incapacitated), he is immune to magic that allows other creatures to read his thoughts, determine whether he is lying, know his alignment, or know his creature type. Creatures can telepathically communicate with Lazav only if he allows it.

## Actions

***Multiattack.*** Lazav makes three shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+13|noform|noparens|text(+13)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+7|noform|noparens|avg|text(10)` (`1d6 + 7`) piercing damage plus `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) psychic damage, and the target has disadvantage on the next attack roll it makes before Lazav's next turn.

## Legendary Actions

***Attack.*** Lazav makes a weapon attack.

***Cast a Spell (Costs 2 Actions).*** Lazav casts one of his innate spells.

***Shifting Nightmare (Costs 3 Actions).*** Lazav rapidly takes the form of several nightmarish creatures, lashing out at all nearby. Each creature within 10 feet of Lazav must succeed on a DC 21 Dexterity saving throw or take `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) damage of a type chosen by Lazav: acid, cold, fire, lightning, or necrotic.
```
^statblock