---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/17
- 5e/monster/environment/desert
- 5e/monster/environment/planar
- 5e/monster/environment/upper
- 5e/monster/size/large
- 5e/monster/type/celestial
aliases:
- Sphinx of Valor
---
# Sphinx of Valor
*Source: Monster Manual (2024) p. 294. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Sphinxes of valor guard world-changing or dangerous secrets—evidence of weird truths, deadly Artifacts, and things that shouldn't exist. They inhabit hidden, magical sites and hold their duty above mortal life. If threatened, a sphinx of valor defends its charge with its supernaturally empowered roar and fierce strikes.

## Sphinxes

*Collectors and Keepers of Secrets*

- **Habitat.** Desert, Planar (Upper Planes)  
- **Treasure.** Arcana  

Sphinxes protect the secrets of the multiverse. Formed from the spirits of sages and explorers, sphinxes know the power of truth and the importance of preserving it. They share their wisdom only with those who prove themselves wise or overcome tests of worthiness, such as riddles or battles with dangerous beasts. Through their existences, sphinxes might change form as they gain more nuanced understanding of cosmic enigmas.

### Sphinx Lairs

Sphinxes typically dwell in places that hold great knowledge or prophetic magic.

> [!quote]  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging eternally

> [!note]
> Answer to the riddle of White Plume Mountain: The Moon.

## Statblock

```ad-statblock
title: Sphinx of Valor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Sphinx%20of%20Valor.webp#token)
*Large celestial, Lawful Neutral*

- **Armor Class** 17
- **Hit Points** 199 (`19d10 + 95`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|10 (+0)|20 (+5)|16 (+3)|23 (+6)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Constitution +11, Intelligence +9, Wisdom +12
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +9, [Perception](rules/5e/skills.md#Perception) +12, [Religion](rules/5e/skills.md#Religion) +15
- **Senses** truesight 120 ft., passive Perception 22
- **Damage Resistances** necrotic, radiant
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [frightened](rules/5e/conditions.md#Frightened)
- **Languages** Celestial, Common
- **Challenge** 17

## Traits

***Inscrutable.*** No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom ([Insight](rules/5e/skills.md#Insight)) checks made to ascertain its intentions or sincerity are made with [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md).

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the sphinx fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The sphinx makes two Claw attacks and uses Roar.

***Claw.*** *Melee Attack Roll:* `dice:1d20+12|noform|noparens|text(+12)`, reach 5 ft. *Hit:* `dice:4d6+6|noform|noparens|avg|text(20)` (`4d6 + 6`) Slashing damage.

***Roar (3/Day).*** The sphinx emits a magical roar. Whenever it roars, the roar has a different effect, as detailed below (the sequence resets when it takes a [Long Rest](rules/5e/variant-rules/long-rest-xphb.md)):

- **First Roar.** *Wisdom Saving Throw:* DC 20, each enemy in a 500-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the sphinx. *Failure:* The target has the [Frightened](rules/5e/conditions.md#Frightened) condition for 1 minute.  
- **Second Roar.** *Wisdom Saving Throw:* DC 20, each enemy in a 500-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the sphinx. *Failure:* The target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  
- **Third Roar.** *Constitution Saving Throw:* DC 20, each enemy in a 500-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the sphinx. *Failure:* `dice:8d10|noform|noparens|avg|text(44)` (`8d10`) Thunder damage, and the target has the [Prone](rules/5e/conditions.md#Prone) condition. *Success:* Half damage only.  

***Spellcasting.*** The sphinx casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 20):

**At will:** [Detect Evil and Good](compendium/5e/spells/detect-evil-and-good.md), [Thaumaturgy](compendium/5e/spells/thaumaturgy.md)

**1/day each:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Dispel Magic](compendium/5e/spells/dispel-magic.md), [Greater Restoration](compendium/5e/spells/greater-restoration.md), [Heroes' Feast](compendium/5e/spells/heroes-feast.md), [Zone of Truth](compendium/5e/spells/zone-of-truth.md)

## Legendary Actions

***Arcane Prowl.*** The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.

***Weight of Years.*** *Constitution Saving Throw:* DC 16, one creature the sphinx can see within 120 feet. *Failure:* The target gains 1 [Exhaustion](rules/5e/conditions.md#Exhaustion) level. While the target has any [Exhaustion](rules/5e/conditions.md#Exhaustion) levels, it appears `dice:3d10|noform|noparens|avg` (`3d10`) years older. *Failure or Success:* The sphinx can't take this action again until the start of its next turn.

![Sphinx](compendium/5e/bestiary/legendary-group/sphinx.md)
```
^statblock

## Environment

desert, planar, upper