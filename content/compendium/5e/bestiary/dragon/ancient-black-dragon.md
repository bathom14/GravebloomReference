---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/21
- 5e/monster/environment/swamp
- 5e/monster/size/gargantuan
- 5e/monster/type/dragon/chromatic
aliases:
- Ancient Black Dragon
---
# Ancient Black Dragon
*Source: Monster Manual (2024) p. 40. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient black dragons plot the ruin of whole realms. They seek magic to corrupt the land, raise undead hordes, bind fiends, and replicate magical disasters. Ancient black dragons strive to create vast, dead domains where they are the greatest things that remain.

## Black Dragons

*Dragons of Decay and Despair*

- **Habitat.** Swamp  
- **Treasure.** Relics  

Black dragons delight in suffering and ruin. While other chromatic dragons scheme for power and wealth, these dragons seek to tear down all they see and rule over what remains.

Black dragons are terrifying creatures with curved horns and withered visages suggestive of fiendish skulls. They typically inhabit stagnant swamps, crumbling ruins, or places of magical or environmental corruption. Their acid breath scars their domains, eroding the features from ancient statues and leaving nature with festering wounds.

Black dragons hoard tarnished symbols of hope and relics of fallen empires. The more sought-after the treasure, the more black dragons prize it—particularly if they were responsible for it being lost.

### Black Dragon Lairs

Black dragons lurk in dismal ruins, polluted bogs, or other sites gripped by decay.

## Statblock

```ad-statblock
title: Ancient Black Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Black%20Dragon.webp#token)
*Gargantuan dragon (chromatic), Chaotic Evil*

- **Armor Class** 22
- **Hit Points** 367 (`21d20 + 147`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|25 (+7)|16 (+3)|15 (+2)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Wisdom +9
- **Skills** [Perception](rules/5e/skills.md#Perception) +16, [Stealth](rules/5e/skills.md#Stealth) +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** acid
- **Languages** Common, Draconic
- **Challenge** 21

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Melf's Acid Arrow](compendium/5e/spells/melfs-acid-arrow.md) (level 4 version).

***Rend.*** *Melee Attack Roll:* `dice:1d20+15|noform|noparens|text(+15)`, reach 15 ft. *Hit:* `dice:2d8+8|noform|noparens|avg|text(17)` (`2d8 + 8`) Slashing damage plus `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) Acid damage.

***Acid Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 22, each creature in a 90-foot-long, 10-foot-wide [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md). *Failure:* `dice:15d8|noform|noparens|avg|text(67)` (`15d8`) Acid damage. *Success:* Half damage.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, `dice:1d20+13|noform|noparens|text(+13)` to hit with spell attacks):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Fear](compendium/5e/spells/fear.md), [Melf's Acid Arrow](compendium/5e/spells/melfs-acid-arrow.md) (level 4 version)

**1/day each:** [Create Undead](compendium/5e/spells/create-undead.md), [Speak with Dead](compendium/5e/spells/speak-with-dead.md), [Vitriolic Sphere](compendium/5e/spells/vitriolic-sphere.md) (level 5 version)

## Legendary Actions

***Cloud of Insects.*** *Dexterity Saving Throw:* DC 21, one creature the dragon can see within 120 feet. *Failure:* `dice:6d10|noform|noparens|avg|text(33)` (`6d10`) Poison damage, and the target has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on saving throws to maintain [Concentration](rules/5e/conditions.md#Concentration) until the end of its next turn. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Frightful Presence.*** The dragon uses Spellcasting to cast [Fear](compendium/5e/spells/fear.md). The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Black Dragon](compendium/5e/bestiary/legendary-group/black-dragon.md)
```
^statblock

## Environment

swamp