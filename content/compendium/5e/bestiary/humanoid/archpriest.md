---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/12
- 5e/monster/environment/any
- 5e/monster/size/small-or-medium
- 5e/monster/type/humanoid/cleric
aliases:
- Archpriest
---
# Archpriest
*Source: Monster Manual (2024) p. 248, Dragon Delves*  

By forging connections with divine beings and mastering mystical truths, archpriests become conduits for godly intentions and other supernatural forces. Their magic allows them to work wonders, whether to share the benevolence of their faiths or to vent divine wrath. Some archpriests attract vast followings as they claim to speak for divine forces, while others undertake personal spiritual journeys and seek to transcend mortal concerns.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](archpriest.md#^priest-roles)`

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
title: Archpriest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Archpriest.webp#token)
*Small or Medium humanoid (cleric), Neutral*

- **Armor Class** 16
- **Hit Points** 240 (`32d8 + 96`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|17 (+3)|14 (+2)|21 (+5)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +7, Constitution +7, Intelligence +6, Wisdom +9
- **Skills** [Insight](rules/5e/skills.md#Insight) +9, [Medicine](rules/5e/skills.md#Medicine) +9, [Perception](rules/5e/skills.md#Perception) +9, [Religion](rules/5e/skills.md#Religion) +10
- **Senses** passive Perception 19
- **Languages** Common plus two other languages
- **Challenge** 12

## Actions

***Multiattack.*** The archpriest makes three Radiant Burst attacks.

***Radiant Burst.*** *Melee  or Ranged Attack Roll:* `dice:1d20+9|noform|noparens|text(+9)`, reach 5 ft. or range 60 ft. *Hit:* `dice:4d10+5|noform|noparens|avg|text(27)` (`4d10 + 5`) Radiant damage.

***Holy Word (Recharge 4-6).*** *Wisdom Saving Throw:* DC 17, each enemy in a 20-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the archpriest. *Failure:* `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) Radiant damage, and the target has the [Stunned](rules/5e/conditions.md#Stunned) condition until the end of the archpriest's next turn. *Success:* Half damage only.

***Spellcasting.*** The archpriest casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will:** [Light](compendium/5e/spells/light.md), [Thaumaturgy](compendium/5e/spells/thaumaturgy.md)

**1/day each:** [Flame Strike](compendium/5e/spells/flame-strike.md) (level 6 version), [Greater Restoration](compendium/5e/spells/greater-restoration.md), [Raise Dead](compendium/5e/spells/raise-dead.md), [Zone of Truth](compendium/5e/spells/zone-of-truth.md)

## Bonus Actions

***Divine Aid (3/Day).*** The priest casts [Bless](compendium/5e/spells/bless.md), [Dispel Magic](compendium/5e/spells/dispel-magic.md), [Healing Word](compendium/5e/spells/healing-word.md), or [Lesser Restoration](compendium/5e/spells/lesser-restoration.md), using the same spellcasting ability as Spellcasting.

```
^statblock

## Environment

any