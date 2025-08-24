---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/2
- 5e/monster/environment/any
- 5e/monster/size/small-or-medium
- 5e/monster/type/humanoid/cleric
aliases:
- Priest
---
# Priest
*Source: Monster Manual (2024) p. 248, Dragon Delves. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Priests draw on their beliefs to heal the needful and smite their foes. They can channel their faith as spells and empower their weapons with divine might.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](priest.md#^priest-roles)`

| dice: 1d10 | The Priest Is... |
|------------|------------------|
| 1 | An ascetic who keeps wicked spirits at bay. |
| 2 | An elder who speaks for the dead. |
| 3 | An exorcist who hunts wicked spirits. |
| 4 | A follower of a god no one has heard of. |
| 5 | A mediator and teacher of traditional ways. |
| 6 | A philosopher devoted to a concept, multiversal view, or plane of existence. |
| 7 | The reincarnation of an ancient faith leader. |
| 8 | A ritualist who uses tinctures and performances to access the divine. |
| 9 | A shaman whose medicines ease many ills. |
| 10 | A zealot who wages war for a divine cause. |
^priest-roles

> [!quote]  
> 
> Shining One, light my hours. Enkindle my soul, and inspire my deeds. Chase the shadows from my path, and let me walk in your brilliance.


## Statblock

```ad-statblock
title: Priest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Priest.webp#token)
*Small or Medium humanoid (cleric), Neutral*

- **Armor Class** 13
- **Hit Points** 38 (`7d8 + 7`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|12 (+1)|13 (+1)|16 (+3)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Medicine](rules/5e/skills.md#Medicine) +7, [Perception](rules/5e/skills.md#Perception) +5, [Religion](rules/5e/skills.md#Religion) +5
- **Senses** passive Perception 15
- **Languages** Common plus one other language
- **Challenge** 2

## Actions

***Multiattack.*** The priest makes two attacks, using Mace or Radiant Flame in any combination.

***Mace.*** *Melee Attack Roll:* `dice:1d20+5|noform|noparens|text(+5)`, reach 5 ft. *Hit:* `dice:1d6+3|noform|noparens|avg|text(6)` (`1d6 + 3`) Bludgeoning damage plus `dice:2d4|noform|noparens|avg|text(5)` (`2d4`) Radiant damage.

***Radiant Flame.*** *Ranged Attack Roll:* `dice:1d20+5|noform|noparens|text(+5)`, range 60 ft. *Hit:* `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) Radiant damage.

***Spellcasting.*** The priest casts one of the following spells, using Wisdom as the spellcasting ability:

**At will:** [Light](compendium/5e/spells/light.md), [Thaumaturgy](compendium/5e/spells/thaumaturgy.md)

**1/day:** [Spirit Guardians](compendium/5e/spells/spirit-guardians.md)

## Bonus Actions

***Divine Aid (3/Day).*** The priest casts [Bless](compendium/5e/spells/bless.md), [Dispel Magic](compendium/5e/spells/dispel-magic.md), [Healing Word](compendium/5e/spells/healing-word.md), or [Lesser Restoration](compendium/5e/spells/lesser-restoration.md), using the same spellcasting ability as Spellcasting.

```
^statblock

## Environment

any