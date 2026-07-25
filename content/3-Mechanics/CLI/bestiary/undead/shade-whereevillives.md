---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/incorporeal
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shade
---
# [Shade](3-Mechanics\CLI\bestiary\undead/shade-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 246*  

```statblock
"name": "Shade (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "incorporeal, Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "11"
"hp": !!int "8"
"modifier": !!int "1"
"stats":
  - !!int "1"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
"speed": "0 ft., fly 50 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "the languages they knew in life"
"cr": "1"
"traits":
  - "desc": "The shade can move through other creatures and objects as if they were\
      \ difficult terrain. The shade is destroyed if they end their turn inside an\
      \ object."
    "name": "Incorporeal Movement"
  - "desc": "If the shade takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the shade takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If an enemy starts their turn within 5 feet of three or more shades,\
      \ the enemy must succeed on a Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the shades until the start of their next turn. The DC for this saving throw\
      \ equals 10 plus the number of shades within 5 feet of the enemy. On a successful\
      \ save, the enemy is immune to the Terrifying trait of all shades for the next\
      \ 24 hours."
    "name": "Terrifying"
"actions":
  - "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 1\
      \ necrotic damage."
    "name": "Life Drain (Group Attack)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/undead/token/shade-whereevillives.png"
```
^statblock