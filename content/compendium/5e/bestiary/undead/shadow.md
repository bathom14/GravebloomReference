---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/1-2
- 5e/monster/environment/planar
- 5e/monster/environment/shadowfell
- 5e/monster/environment/underdark
- 5e/monster/environment/urban
- 5e/monster/size/medium
- 5e/monster/type/undead
aliases:
- Shadow
---
# Shadow
*Source: Monster Manual (2024) p. 272. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Shadow

*Disembodied, Life-Drinking Shade*

- **Habitat.** Planar (Shadowfell), Underdark, Urban  
- **Treasure.** None  

Shadows are incorporeal Undead that feed on life. They resent the living for possessing the potential and vitality lost to them.

Shadows lurk in dark, lonely places, typically sites that were meaningful to them in life or cursed places with ties to death, sinister magic, or the Shadowfell. Their victims rise as new shadows and prey on the living.

Shadows might resemble the silhouettes of who they were in life or take on more menacing forms. Roll on or choose a result from the Shadow Shapes table to inspire a shadow's form and haunting.

**Shadow Shapes**

`dice: [](shadow.md#^shadow-shapes)`

| dice: 1d6 | The Shadow Appears As... |
|-----------|--------------------------|
| 1 | A distorted stalker that lurks in the woods. |
| 2 | A fiend that dwells near a wicked ritual site. |
| 3 | Grasping hands that haunt a miser's home. |
| 4 | A grim storybook character that follows those who speak its name. |
| 5 | Its target, acting in eerie pantomime. |
| 6 | An ominous priest that haunts a defiled site. |
^shadow-shapes

```ad-statblock
title: Shadow
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Shadow.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 27 (`5d8 + 5`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|13 (+1)| 6 (-2)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Stealth](rules/5e/skills.md#Stealth) +6
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** acid, cold, fire, lightning, thunder
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [grappled](rules/5e/conditions.md#Grappled), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned), [prone](rules/5e/conditions.md#Prone), [restrained](rules/5e/conditions.md#Restrained), [unconscious](rules/5e/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 1/2

## Traits

***Amorphous.*** The shadow can move through a space as narrow as 1 inch without expending extra movement to do so.

***Sunlight Weakness.*** While in sunlight, the shadow has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on [D20 Tests](rules/5e/variant-rules/d20-test-xphb.md).

## Actions

***Draining Swipe.*** *Melee Attack Roll:* `dice:1d20+4|noform|noparens|text(+4)`, reach 5 ft. *Hit:* `dice:1d6+2|noform|noparens|avg|text(5)` (`1d6 + 2`) Necrotic damage, and the target's Strength score decreases by `dice:1d4|noform|noparens|avg` (`d4`). The target dies if this reduces that score to 0. If a Humanoid is slain by this attack, a Shadow rises from the corpse `dice:1d4|noform|noparens|avg` (`d4`) hours later.

## Bonus Actions

***Shadow Stealth.*** While in [Dim Light](rules/5e/variant-rules/dim-light-xphb.md) or [Darkness](rules/5e/variant-rules/darkness-xphb.md), the shadow takes the Hide action.
```
^statblock

## Environment

planar, shadowfell, underdark, urban