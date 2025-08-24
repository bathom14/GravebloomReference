---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/10
- 5e/monster/environment/desert
- 5e/monster/environment/forest
- 5e/monster/environment/planar
- 5e/monster/environment/upper
- 5e/monster/size/large
- 5e/monster/type/celestial
aliases:
- Guardian Naga
---
# Guardian Naga
*Source: Monster Manual (2024) p. 161. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Guardian Naga

*Enduring Serpentine Lore Keeper*

- **Habitat.** Desert, Forest, Planar (Upper Planes)  
- **Treasure.** Relics  

Guardian nagas are immortal, serpentine scholars that possess perfect memories. They collect the histories and lore of those they live among, guarding cultures' stories and passing them on to new generations with infallible accuracy. Guardian nagas that outlive their host civilizations might linger in whatever ruins remain, preserving the civilizations' stories so their lost people might live on.

Roll on or choose a result from the Guardian Naga Lore table to inspire what a naga knows.

**Guardian Naga Lore**

`dice: [](guardian-naga.md#^guardian-naga-lore)`

| dice: 1d8 | The Guardian Naga Recalls... |
|-----------|------------------------------|
| 1 | The last words of an ancient sage or leader. |
| 2 | The location of a hidden city or continent. |
| 3 | A magic word, password, or riddle's answer. |
| 4 | The names of all who have told it stories. |
| 5 | An otherwise forgotten ritual or spell. |
| 6 | Recipes using regional ingredients. |
| 7 | Stories of forgotten gods and local spirits. |
| 8 | The vulnerabilities of a legendary monster. |
^guardian-naga-lore

```ad-statblock
title: Guardian Naga
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Guardian%20Naga.webp#token)
*Large celestial, Lawful Good*

- **Armor Class** 18
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|18 (+4)|16 (+3)|16 (+3)|19 (+4)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Constitution +7, Intelligence +7, Wisdom +8, Charisma +8
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +11, [History](rules/5e/skills.md#History) +11, [Religion](rules/5e/skills.md#Religion) +11
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned), [restrained](rules/5e/conditions.md#Restrained)
- **Languages** Celestial, Common
- **Challenge** 10

## Traits

***Celestial Restoration.*** If the naga dies, it returns to life in `dice:1d6|noform|noparens|avg` (`d6`) days and regains all its [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) unless [Dispel Evil and Good](compendium/5e/spells/dispel-evil-and-good.md) is cast on its remains.

## Actions

***Multiattack.*** The naga makes two Bite attacks. It can replace any attack with a use of Poisonous Spittle.

***Bite.*** *Melee Attack Roll:* `dice:1d20+8|noform|noparens|text(+8)`, reach 10 ft. *Hit:* `dice:2d12+4|noform|noparens|avg|text(17)` (`2d12 + 4`) Piercing damage plus `dice:4d10|noform|noparens|avg|text(22)` (`4d10`) Poison damage.

***Poisonous Spittle.*** *Constitution Saving Throw:* DC 16, one creature the naga can see within 60 feet. *Failure:* `dice:7d8|noform|noparens|avg|text(31)` (`7d8`) Poison damage, and the target has the [Blinded](rules/5e/conditions.md#Blinded) condition until the start of the naga's next turn. *Success:* Half damage only.

***Spellcasting.*** The naga casts one of the following spells, requiring no Somatic or Material components and using Wisdom as the spellcasting ability (spell save DC 16):

**At will:** [Thaumaturgy](compendium/5e/spells/thaumaturgy.md)

**1/day each:** [Clairvoyance](compendium/5e/spells/clairvoyance.md), [Cure Wounds](compendium/5e/spells/cure-wounds.md) (level 6 version), [Flame Strike](compendium/5e/spells/flame-strike.md) (level 6 version), [Geas](compendium/5e/spells/geas.md), [True Seeing](compendium/5e/spells/true-seeing.md)
```
^statblock

## Environment

desert, forest, planar, upper