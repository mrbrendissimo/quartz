---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rotting Zombie
---
# [Rotting Zombie](3-Mechanics\CLI\bestiary\undead/rotting-zombie-fleemortals.md)
*Source: Flee, Mortals! p. 254*  

```statblock
"name": "Rotting Zombie (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "8"
"hp": !!int "6"
"modifier": !!int "-2"
"stats":
  - !!int "13"
  - !!int "6"
  - !!int "12"
  - !!int "3"
  - !!int "6"
  - !!int "5"
"speed": "20 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands the languages they knew in life but can't speak"
"cr": "1/4"
"traits":
  - "desc": "If the zombie takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the zombie takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If an enemy starts their turn within 5 feet of three or more rotting\
      \ zombies who can see them, the enemy's speed is reduced by 5 feet for each\
      \ rotting zombie within 5 feet of them until the start of their next turn. If\
      \ this reduces the enemy's walking speed to 0, they are [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ for the duration."
    "name": "Overwhelm"
  - "desc": "The first time a zombie is reduced to 0 hit points by damage other than\
      \ radiant damage but their body isn't destroyed, they regain hit points equal\
      \ to their hit point maximum, and they fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and are [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated) until\
      \ the start of their next turn."
    "name": "Rise Again"
"actions":
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 bludgeoning\
      \ damage."
    "name": "Slam (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/rotting-zombie-fleemortals.webp"
```
^statblock