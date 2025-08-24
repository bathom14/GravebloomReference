---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/24
- 5e/monster/environment/forest
- 5e/monster/environment/grassland
- 5e/monster/size/gargantuan
- 5e/monster/type/dragon/metallic
aliases:
- Ancient Gold Dragon
---
# Ancient Gold Dragon
*Source: Monster Manual (2024) p. 146. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient gold dragons are wise and mysterious. Many aid virtuous groups, guiding them in secret or patronizing them from afar. Only when stakes are at their highest do ancient gold dragons reveal themselves in all their majesty.

## Gold Dragons

*Dragons of Hope and Majesty*

- **Habitat.** Forest, Grassland  
- **Treasure.** Arcana  

Gold dragons work to make the world a better place. The most powerful of the metallic dragons, these awe-inspiring dragons strive to protect that which is good and bend fate toward a brighter future. Their kind dispositions don't prevent gold dragons from engaging in combat when necessary, though, and they exhale brilliant flames and weakening magic to rout their foes.

Gold dragons favor grasslands and pristine forests, frequently dwelling near awe-inspiring natural wonders or guarding monuments from ancient civilizations. In their lairs, gold dragons hoard coins and gems, but they frequently put their treasure to use in pursuit of greater goals. They often use their riches to buy rare lore books, pay informants, or patronize idealistic adventurers.

### Gold Dragon Lairs

Gold dragons make their homes in places of natural and magical wonder.

## Statblock

```ad-statblock
title: Ancient Gold Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ancient%20Gold%20Dragon.webp#token)
*Gargantuan dragon (metallic), Lawful Good*

- **Armor Class** 22
- **Hit Points** 546 (`28d20 + 252`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|14 (+2)|29 (+9)|18 (+4)|17 (+3)|28 (+9)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Wisdom +10
- **Skills** [Insight](rules/5e/skills.md#Insight) +10, [Perception](rules/5e/skills.md#Perception) +17, [Persuasion](rules/5e/skills.md#Persuasion) +16, [Stealth](rules/5e/skills.md#Stealth) +9
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 27
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 24

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 4 version) or (B) Weakening Breath.

***Rend.*** *Melee Attack Roll:* `dice:1d20+17|noform|noparens|text(+17)` to hit, reach 15 ft. *Hit:* `dice:2d8+10|noform|noparens|avg|text(19)` (`2d8 + 10`) Slashing damage plus `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 24, each creature in a 90-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:13d10|noform|noparens|avg|text(71)` (`13d10`) Fire damage. *Success:* Half damage.

***Weakening Breath.*** *Strength Saving Throw:* DC 24, each creature that isn't currently affected by this breath in a 90-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on Strength-based [D20 Tests](rules/5e/variant-rules/d20-test-xphb.md) and subtracts `dice:1d10|noform|noparens|avg|text(5)` (`d10`) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 24, `dice:1d20+16|noform|noparens|text(+16)` to hit with spell attacks):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 4 version), [Shapechange](compendium/5e/spells/shapechange.md) (Beast or Humanoid form only, no [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Flame Strike](compendium/5e/spells/flame-strike.md) (level 6 version), [Word of Recall](compendium/5e/spells/word-of-recall.md), [Zone of Truth](compendium/5e/spells/zone-of-truth.md)

## Legendary Actions

***Banish.*** *Charisma Saving Throw:* DC 24, one creature the dragon can see within 120 feet. *Failure:* `dice:7d6|noform|noparens|avg|text(24)` (`7d6`) Force damage, and the target has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Guiding Light.*** The dragon uses Spellcasting to cast [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 4 version).

***Pounce.*** The dragon moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Gold Dragon](compendium/5e/bestiary/legendary-group/gold-dragon.md)
```
^statblock

## Environment

forest, grassland