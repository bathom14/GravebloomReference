---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpmm
- 5e/monster/cr/12
- 5e/monster/environment/forest
- 5e/monster/environment/mountain
- 5e/monster/environment/swamp
- 5e/monster/environment/underwater
- 5e/monster/size/medium
- 5e/monster/type/humanoid/druid
aliases:
- Archdruid
---
# Archdruid
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48, Volo's Guide to Monsters p. 210, Waterdeep: Dungeon of the Mad Mage p. 311*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](compendium/5e/bestiary/humanoid/druid.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

`dice: [](archdruid-mpmm.md#^archdruid-favored-shapes)`

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](compendium/5e/bestiary/elemental/air-elemental.md) |
| 2 | [Earth elemental](compendium/5e/bestiary/elemental/earth-elemental.md) |
| 3 | [Fire elemental](compendium/5e/bestiary/elemental/fire-elemental.md) |
| 4 | [Giant crocodile](compendium/5e/bestiary/beast/giant-crocodile.md) |
| 5 | [Mammoth](compendium/5e/bestiary/beast/mammoth.md) |
| 6 | [Flail snail](compendium/5e/bestiary/elemental/flail-snail-mpmm.md) |
| 7 | [Triceratops](compendium/5e/bestiary/beast/triceratops.md) |
| 8 | [Water elemental](compendium/5e/bestiary/elemental/water-elemental.md) |
^archdruid-favored-shapes

```ad-statblock
title: Archdruid
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Archdruid.webp#token)
*Medium humanoid (druid), Any alignment*

- **Armor Class** 14 ([hide armor](compendium/5e/items/hide-armor-phb.md))
- **Hit Points** 154 (`28d8 + 28`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|14 (+2)|12 (+1)|12 (+1)|20 (+5)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +5, Wisdom +9
- **Skills** [Medicine](rules/5e/skills.md#Medicine) +9, [Nature](rules/5e/skills.md#Nature) +5, [Perception](rules/5e/skills.md#Perception) +9
- **Senses** passive Perception 19
- **Languages** Druidic plus any two languages
- **Challenge** 12

## Actions

***Multiattack.*** The archdruid makes three Staff or Wildfire attacks. It can replace one attack with a use of Spellcasting.

***Staff.*** *Melee Weapon Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|noparens|avg|text(5)` (`1d6 + 2`) bludgeoning damage plus `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) poison damage.

***Wildfire.*** *Ranged Spell Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, range 120 ft., one target. *Hit:* `dice:6d6+5|noform|noparens|avg|text(26)` (`6d6 + 5`) fire damage, and the target is [blinded](rules/5e/conditions.md#Blinded) until the start of the druid's next turn.

***Spellcasting.*** The archdruid casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 17):

**At will:** [beast sense](compendium/5e/spells/beast-sense.md), [entangle](compendium/5e/spells/entangle.md), [speak with animals](compendium/5e/spells/speak-with-animals.md)

**3/day each:** [animal messenger](compendium/5e/spells/animal-messenger.md), [dominate beast](compendium/5e/spells/dominate-beast.md), [faerie fire](compendium/5e/spells/faerie-fire.md), [tree stride](compendium/5e/spells/tree-stride.md)

**1/day each:** [commune with nature](compendium/5e/spells/commune-with-nature.md) (as an action), [mass cure wounds](compendium/5e/spells/mass-cure-wounds.md)

## Bonus Actions

***Change Shape (2/Day).*** The archdruid magically transforms into a Beast or an Elemental with a challenge rating of 6 or less and can remain in that form for up to 9 hours. The archdruid can choose whether its equipment falls to the ground, melds with its new form, or is worn by the new form. The archdruid reverts to its true form if it dies or falls [unconscious](rules/5e/conditions.md#Unconscious). The archdruid can revert to its true form using a bonus action.

While in a new form, the archdruid's stat block is replaced by the stat block of that form, except the archdruid keeps its current hit points, its hit point maximum, this bonus action, its languages and ability to speak, and its Spellcasting action.

The new form's attacks count as magical for the purpose of overcoming resistances and immunity to nonmagical attacks.
```
^statblock

## Environment

forest, mountain, swamp, underwater