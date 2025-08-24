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
- Death Cultist
---
# Death Cultist
*Source: Monster Manual (2024) p. 86*  

Death cultists revel in nihilistic forces, embracing them as paths to undeath, multiversal purity, or entropic inevitability. These cultists serve powerful undead beings, apocalyptic prophecies, or immortals with power over death, such as Acererak, Kyuss, Orcus, Vecna, or Wee Jas.

## Cultists

*Doomsayers and Fanatics*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Cultists use magic and extreme measures to spread radical beliefs. Some privately pursue esoteric secrets, while others form shadowy cabals seeking to bring about terrifying ends. Cultists often follow obscure mystical traditions or obsess over interpretations of ancient prophecies. They might worship supernatural patrons—deities, otherworldly creatures, manipulative alien minds, or stranger forces. Roll on or choose a result from the Cultist Agendas table to inspire what a cultist seeks to achieve.

**Cultist Agendas**

`dice: [](death-cultist.md#^cultist-agendas)`

| dice: 1d6 | The Cultist Strives To... |
|-----------|---------------------------|
| 1 | Bring about the end of a dominant order, an age, or the world. |
| 2 | Burn away the comfortable lies of reality, revealing forgotten or terrible truths. |
| 3 | Expand their faith though mind control or supernatural coercion. |
| 4 | Make global changes, like sinking the land or awakening volcanoes. |
| 5 | Remake life on a mass scale, altering other creatures' bodies or spiritual beings. |
| 6 | Summon their deity or its herald, weapon, or realm into their world. |
^cultist-agendas

### Occult Symbols

Cults often identify with symbols that exemplify their beliefs. Such symbols might mark objects important to the cult, as well as the dress and bodies of cultists themselves. These symbols might be broadly understandable, or they might have meaning only to cultists. Roll twice on or choose results from the Cult Symbols table to inspire a cult's icons.

**Cult Symbols**

`dice: [](death-cultist.md#^cult-symbols)`

| dice: 1d10 | The Symbol Is... | Depicted As... |
|------------|------------------|----------------|
| 1 | An alchemical sign | A calendar or map |
| 2 | An animal | A crest or as heraldry |
| 3 | A celestial body | An elaborate diagram |
| 4 | A deity's icon | A metaphorical image |
| 5 | An element | A mystical being |
| 6 | An eye | Part of an equation |
| 7 | A geometric shape | A repeating pattern |
| 8 | A letter or number | A series of scratches |
| 9 | Part of a monster | A simple pictogram |
| 10 | A skull | A weapon or tool |
^cult-symbols

### Cult Members

Cults often form hierarchies around a charismatic or domineering leader. While cult members might work independently, they take their orders from superiors with greater supernatural powers. 

### Types of Cultists

Cults can organize around any mystical tradition, but many serve supernatural beings. Cult members often have abilities tied to the forces they worship.

> [!quote] A quote from Rites of the Cult of Elemental Evil  
> 
> Dread Tharizdun, power of the Elder Elemental Eye and master of all destructive forces, I am the Champion of Elemental Evil and am ready to carry out your wishes.


## Statblock

```ad-statblock
title: Death Cultist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Death%20Cultist.webp#token)
*Small or Medium humanoid, Neutral Evil*

- **Armor Class** 17
- **Hit Points** 127 (`15d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|12 (+1)|18 (+4)|12 (+1)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7, Wisdom +6
- **Skills** [Insight](rules/5e/skills.md#Insight) +6, [Perception](rules/5e/skills.md#Perception) +6, [Religion](rules/5e/skills.md#Religion) +4
- **Senses** passive Perception 16
- **Languages** Common
- **Challenge** 8

## Actions

***Multiattack.*** The cultist makes three attacks, using Dread Scythe or Deathly Ray in any combination.

***Dread Scythe.*** *Melee Attack Roll:* `dice:1d20+7|noform|noparens|text(+7)`, reach 10 ft. *Hit:* `dice:1d10+4|noform|noparens|avg|text(9)` (`1d10 + 4`) Slashing damage plus `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) Necrotic damage, and the target can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) until the end of its next turn.

***Deathly Ray.*** *Ranged Attack Roll:* `dice:1d20+6|noform|noparens|text(+6)`, range 120 ft. *Hit:* `dice:4d10|noform|noparens|avg|text(22)` (`4d10`) Necrotic damage.

***Spellcasting.*** The cultist casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 14):

**At will:** [Speak with Dead](compendium/5e/spells/speak-with-dead.md), [Thaumaturgy](compendium/5e/spells/thaumaturgy.md)

## Bonus Actions

***Spirit Wail (Recharge 5-6).*** *Wisdom Saving Throw:* DC 14, each creature in a 20-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the cultist. *Failure:* `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) Psychic damage, and the target has the [Frightened](rules/5e/conditions.md#Frightened) condition until the end of its next turn. *Success:* Half damage only.
```
^statblock

## Environment

any