---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/17
- 5e/monster/environment/forest
- 5e/monster/environment/grassland
- 5e/monster/size/huge
- 5e/monster/type/dragon/metallic
aliases:
- Adult Gold Dragon
---
# Adult Gold Dragon
*Source: Monster Manual (2024) p. 145. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Adult gold dragons act subtly, frequently changing their shape to resemble harmless animals or cultivating personas so they can pass as common people.

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
title: Adult Gold Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Adult%20Gold%20Dragon.webp#token)
*Huge dragon (metallic), Lawful Good*

- **Armor Class** 19
- **Hit Points** 243 (`18d12 + 126`)
- **Speed** 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|14 (+2)|25 (+7)|16 (+3)|15 (+2)|24 (+7)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +8, Wisdom +8
- **Skills** [Insight](rules/5e/skills.md#Insight) +8, [Perception](rules/5e/skills.md#Perception) +14, [Persuasion](rules/5e/skills.md#Persuasion) +13, [Stealth](rules/5e/skills.md#Stealth) +8
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 24
- **Damage Immunities** fire
- **Languages** Common, Draconic
- **Challenge** 17

## Traits

***Amphibious.*** The dragon can breathe air and water.

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 2 version) or (B) Weakening Breath.

***Rend.*** *Melee Attack Roll:* `dice:1d20+14|noform|noparens|text(+14)`, reach 10 ft. *Hit:* `dice:2d8+8|noform|noparens|avg|text(17)` (`2d8 + 8`) Slashing damage plus `dice:1d8|noform|noparens|avg|text(4)` (`d8`) Fire damage.

***Fire Breath (Recharge 5-6).*** *Dexterity Saving Throw:* DC 21, each creature in a 60-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:12d10|noform|noparens|avg|text(66)` (`12d10`) Fire damage. *Success:* Half damage.

***Weakening Breath.*** *Strength Saving Throw:* DC 21, each creature that isn't currently affected by this breath in a 60-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* The target has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on Strength-based [D20 Tests](rules/5e/variant-rules/d20-test-xphb.md) and subtracts `dice:1d6|noform|noparens|avg|text(3)` (`d6`) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

***Spellcasting.*** The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, `dice:1d20+13|noform|noparens|text(+13)` to hit with spell attacks):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 2 version), [Shapechange](compendium/5e/spells/shapechange.md) (Beast or Humanoid form only, no [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) gained from the spell, and no Concentration or [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md) required to maintain the spell)

**1/day each:** [Flame Strike](compendium/5e/spells/flame-strike.md), [Zone of Truth](compendium/5e/spells/zone-of-truth.md)

## Legendary Actions

***Banish.*** *Charisma Saving Throw:* DC 21, one creature the dragon can see within 120 feet. *Failure:* `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) Force damage, and the target has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon. *Failure or Success:* The dragon can't take this action again until the start of its next turn.

***Guiding Light.*** The dragon uses Spellcasting to cast [Guiding Bolt](compendium/5e/spells/guiding-bolt.md) (level 2 version).

***Pounce.*** The dragon moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Rend attack.

![Gold Dragon](compendium/5e/bestiary/legendary-group/gold-dragon.md)
```
^statblock

## Environment

forest, grassland