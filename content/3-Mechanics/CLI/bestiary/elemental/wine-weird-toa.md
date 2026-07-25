---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wine Weird
---
# [Wine Weird](3-Mechanics\CLI\bestiary\elemental/wine-weird-toa.md)
*Source: Tomb of Annihilation p. 141*  

```statblock
"name": "Wine Weird (ToA)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"modifier": !!int "3"
"stats":
  - !!int "17"
  - !!int "16"
  - !!int "13"
  - !!int "11"
  - !!int "10"
  - !!int "10"
"speed": "0 ft., swim 60 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "understands Aquan but doesn't speak"
"cr": "3"
"traits":
  - "desc": "The wine weird is [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ while fully immersed in water."
    "name": "Invisible in Water"
  - "desc": "The wine weird dies if it leaves the water to which it is bound or if\
      \ that water is destroyed."
    "name": "Water Bound"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one creature. Hit:\
      \ 13 (3d6 + 3) bludgeoning damage. If the target is Medium or smaller, it is\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 13) and pulled\
      \ 5 feet toward the wine weird. Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ the wine weird tries to drown it, and the wine weird can't constrict another\
      \ target."
    "name": "Constrict"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/wine-weird-toa.webp"
```
^statblock