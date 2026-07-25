---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Zombie
---
# [Zombie](3-Mechanics\CLI\bestiary\undead/zombie-fleemortals.md)
*Source: Flee, Mortals! p. 255*  

```statblock
"name": "Zombie (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Brute"
"alignment": "typically  Lawful Evil"
"ac": !!int "8"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "15"
  - !!int "8"
  - !!int "14"
  - !!int "3"
  - !!int "5"
  - !!int "5"
"speed": "20 ft."
"damage_vulnerabilities": "radiant"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 7"
"languages": "understands the languages they knew in life but can't speak"
"cr": "1/4"
"traits":
  - "desc": "Whenever a creature deals 5 damage or less to the zombie, the zombie\
      \ takes no damage instead."
    "name": "Negative Nerves"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) bludgeoning damage."
    "name": "Slam"
"reactions":
  - "desc": "When the zombie's Negative Nerves trait allows them to ignore damage\
      \ dealt by a creature the zombie can see within 5 feet of them, the zombie makes\
      \ a Slam attack with disadvantage against the creature."
    "name": "Delayed Reflex"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/zombie-fleemortals.png"
```
^statblock