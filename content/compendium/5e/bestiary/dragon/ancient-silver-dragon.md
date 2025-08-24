---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/23
- 5e/monster/environment/mountain
- 5e/monster/environment/urban
- 5e/monster/size/gargantuan
- 5e/monster/type/dragon/metallic
aliases:
- Ancient Silver Dragon
---
# Ancient Silver Dragon
*Source: Monster Manual (2024) p. 280. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient silver dragons pursue world-wide change. They defend their communities and allies, encouraging them to perform deeds worthy of legend. Some set their sights on other worlds and planes of existence, creating extraplanar alliances or combating multiplanar threats. They might have guises in multiple societies and forge generation-spanning friendships with heroic families or valorous groups.

## Silver Dragons

*Dragons of Courage and Fairness*

- **Habitat.** Mountain, Urban  
- **Treasure.** Arcana  

Silver dragons work to preserve peace and encourage greatness. They try to live as examples of decency while remaining watchful against evil.

Silver dragons typically dwell amid snow-capped mountains, though aspirations and congeniality drive some to instead live among cosmopolitan societies. Disguised as humanoids, they ally with artists, historians, knights, and humble leaders who learn from the past to create better futures.

Silver dragons take inspiration from legendary heroes and have grand ambitions. Many collect treasures that reflect these interests, such as histories, ancient art, and the gear of famous champions.

### Silver Dragon Lairs

Silver dragons typically lair in picturesque mountain retreats or on sculpted cloud "islands."

## Statblock

```ad-statblock
title: Ancient Silver Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Silver%20Dragon.webp#token)
*Gargantuan dragon (metallic), Lawful Good*

- **Armor Class** 22
- **Hit Points** 468 (`24d20 + 216`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|10 (+0)|29 (+9)|18 (+4)|15 (+2)|26 (+8)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Wisdom +9
- **Skills** [History](rules/5e/skills.md#History) +11, [Perception](rules/5e/skills.md#Perception) +16, [Stealth](rules/5e/skills.md#Stealth) +7
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 26
- **Damage Immunities** cold
- **Languages** Common, Draconic
- **Challenge** 23

## Traits

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast [Ice Knife](compendium/5e/spells/ice-knife.md) (level 2 version).

***Rend.*** *Melee Attack Roll:* `dice:1d20+17|noform|noparens|text(+17)`, reach 15 ft. *Hit:* `dice:2d8+10|noform|noparens|avg|text(19)` (`2d8 + 10`) Slashing damage plus `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) Cold damage.

***Cold Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 24, each creature in a 90-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:15d8|noform|noparens|avg|text(67)` (`15d8`) Cold damage. *Success:* Half damage.

***Paralyzing Breath.*** *Constitution Saving Throw:* DC 24, each creature in a 90-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *1st Failure:* The target has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition until the end of its next turn, when it repeats the save. *2nd Failure:* The target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 23, `dice:1d20+15|noform|noparens|text(+15)` to hit with spell attacks):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Hold Monster](compendium/5e/spells/hold-monster.md), [Ice Knife](compendium/5e/spells/ice-knife.md) (level 2 version), [Shapechange](compendium/5e/spells/shapechange.md) (Beast or Humanoid form only, no [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Control Weather](compendium/5e/spells/control-weather.md), [Ice Storm](compendium/5e/spells/ice-storm.md) (level 7 version), [Teleport](compendium/5e/spells/teleport.md), [Zone of Truth](compendium/5e/spells/zone-of-truth.md)

## Legendary Actions

***Chill.*** The dragon uses Spellcasting to cast [Hold Monster](compendium/5e/spells/hold-monster.md). The dragon can't take this action again until the start of its next turn.

***Cold Gale.*** *Dexterity Saving Throw:* DC 23, each creature in a 60-foot-long, 10-foot-wide [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md). *Failure:* `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) Cold damage, and the target is pushed up to 30 feet straight away from the dragon. *Success:* Half damage only. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Pounce.*** The dragon moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Silver Dragon](compendium/5e/bestiary/legendary-group/silver-dragon.md)
```
^statblock

## Environment

mountain, urban