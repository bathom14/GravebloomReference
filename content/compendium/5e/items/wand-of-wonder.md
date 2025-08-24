---
obsidianUIMode: preview
cssclasses: json5e-item
tags:
- 5e/compendium/src/5e/xdmg
- 5e/item/attunement/required
- 5e/item/rarity/rare
- 5e/item/wondrous/wand
aliases: 
- "Wand of Wonder"
---
# Wand of Wonder
*Wand, rare (requires attunement)*  

- **Weight**: 1.0 lbs.

This wand has 7 charges. While holding it, you can take a [Magic](rules/5e/actions.md#Magic) action to expend 1 charge while choosing a point within 120 feet of yourself. That location becomes the point of origin of a spell or other magical effect determined by rolling on the Wand of Wonder Effects table. Spells cast from the wand have a save DC of 15. If a spell's maximum range is normally less than 120 feet, it becomes 120 feet when cast from the wand. If an effect has multiple possible subjects, the DM determines randomly which among them are affected.

## Regaining Charges

The wand regains `dice:1d6+1|noform|noparens|avg` (`1d6 + 1`) expended charges daily at dawn. If you expend the wand's last charge, roll `dice:1d20|noform|noparens|avg` (`d20`). On a 1, the wand crumbles into dust and is destroyed.

**Wand of Wonder Effects**

`dice: [](wand-of-wonder.md#^wand-of-wonder-effects)`

| dice: 1d100 | Effect |
|-------------|--------|
| 01-20 | You cast a spell originating from the chosen point. Roll `dice:1d10\|noform\|noparens\|avg` (`d10`) to determine the spell: on a **1-2**, [Darkness](compendium/5e/spells/darkness.md); on a **3-4**, [Faerie Fire](compendium/5e/spells/faerie-fire.md); on a **5-6**, [Fireball](compendium/5e/spells/fireball.md); on a **7-8**, [Slow](compendium/5e/spells/slow.md); on a **9-10**, [Stinking Cloud](compendium/5e/spells/stinking-cloud.md). |
| 21-25 | Nothing happens at the chosen point of origin. Instead, you have the [Stunned](rules/5e/conditions.md#Stunned) condition until the start of your next turn, believing something awesome just happened. |
| 26-30 | You cast [Gust of Wind](compendium/5e/spells/gust-of-wind.md). The [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md) created by the spell extends from you to the chosen point of origin. |
| 31-35 | Nothing happens at the chosen point of origin. Instead, you take `dice:1d6\|noform\|noparens\|avg` (`d6`) Psychic damage. |
| 36-40 | Heavy rain falls for 1 minute in a 120-foot-high, 60-foot-radius [Cylinder](rules/5e/variant-rules/cylinder-area-of-effect-xphb.md) centered on the chosen point of origin. During that time, the area of effect is [Lightly Obscured](rules/5e/variant-rules/lightly-obscured-xphb.md). |
| 41-45 | A cloud of 600 oversized butterflies fills a 60-foot-high, 30-foot-radius [Cylinder](rules/5e/variant-rules/cylinder-area-of-effect-xphb.md) centered on the chosen point of origin. The butterflies remain for 10 minutes, during which time the area of effect is [Heavily Obscured](rules/5e/variant-rules/heavily-obscured-xphb.md). |
| 46-50 | You cast [Lightning Bolt](compendium/5e/spells/lightning-bolt.md). The [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md) created by the spell extends from you to the chosen point of origin. |
| 51-55 | The creature closest to the chosen point of origin is enlarged as if you had cast [Enlarge/Reduce](compendium/5e/spells/enlarge-reduce.md) on it. If the target isn't you and can't be affected by that spell, you become the target instead. |
| 56-60 | A magically formed creature appears in an unoccupied space as close to the chosen point of origin as possible. The creature isn't under your control, acts as it normally would, and disappears after 1 hour or when it drops to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md). Roll `dice:1d4\|noform\|noparens\|avg` (`d4`) to determine which creature appears. On a **1**, a [Rhinoceros](compendium/5e/bestiary/beast/rhinoceros.md) appears; on a **2**, an [Elephant](compendium/5e/bestiary/beast/elephant.md) appears; and on a **3-4**, a [Rat](compendium/5e/bestiary/beast/rat.md) appears. |
| 61-64 | Grass covers a 60-foot-radius circle of ground, with the center of that circle as close to the chosen point of origin as possible. Grass that's already there grows to ten times its normal size and remains overgrown for 1 minute. |
| 65-68 | An object of the DM's choice disappears into the Ethereal Plane. The object must be neither worn nor carried, within 120 feet of the chosen point of origin, and no larger than 10 feet in any dimension. If there are no such objects in range, nothing happens. |
| 69-72 | Nothing happens at the chosen point of origin. Instead, you shrink as if you had cast [Enlarge/Reduce](compendium/5e/spells/enlarge-reduce.md) on yourself and remain in that state for 1 minute. |
| 73-77 | Leaves grow from the creature nearest to the chosen point of origin. Unless they are picked off, the leaves turn brown and fall off after 24 hours. |
| 78-82 | Nothing happens at the chosen point of origin. Instead, a burst of colorful, shimmering light extends from you in a 30-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md). Each creature in the area must succeed on a DC 15 Constitution saving throw or have the [Blinded](rules/5e/conditions.md#Blinded) condition for 1 minute. A creature repeats the save at the end of each of its turns, ending the effect on itself on a success. |
| 83-87 | Nothing happens at the chosen point of origin. Instead, you cast [Invisibility](compendium/5e/spells/invisibility.md) on yourself. |
| 88-92 | Nothing happens at the chosen point of origin. Instead, a stream of `1d4 × 10` gems, each worth 1 GP, shoots from the wand's tip in a [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md) 30 feet long and 5 feet wide toward the chosen point of origin. Each gem deals 1 Bludgeoning damage, and the total damage of the gems is divided equally among all creatures in the [Line](rules/5e/variant-rules/line-area-of-effect-xphb.md). |
| 93-97 | You cast [Polymorph](compendium/5e/spells/polymorph.md), targeting the creature closest to the chosen point of origin. Roll `dice:1d4\|noform\|noparens\|avg` (`d4`) to determine the target's new form. On a **1**, the new form is a [Black Bear](compendium/5e/bestiary/beast/black-bear.md); on a **2**, the new form is a [Giant Wasp](compendium/5e/bestiary/beast/giant-wasp.md); on a **3-4**, the new form is a [Frog](compendium/5e/bestiary/beast/frog.md). |
| 98-00 | The creature closest to the chosen point of origin makes a DC 15 Constitution saving throw. On a failed save, the creature has the [Restrained](rules/5e/conditions.md#Restrained) condition and begins to turn to stone. While [Restrained](rules/5e/conditions.md#Restrained) in this way, the creature repeats the save at the end of its next turn. On a successful save, the effect ends. On a failed save, the creature has the [Petrified](rules/5e/conditions.md#Petrified) condition instead of the [Restrained](rules/5e/conditions.md#Restrained) condition. The petrification lasts until the creature is freed by the [Greater Restoration](compendium/5e/spells/greater-restoration.md) spell or similar magic. |
^wand-of-wonder-effects

*Source: Dungeon Master's Guide (2024) p. 322. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*