---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swarm of Insects
---
# [Swarm of Insects](3-Mechanics\CLI\bestiary\beast/swarm-of-insects-fleemortals.md)
*Source: Flee, Mortals! p. 41*  

```statblock
"name": "Swarm of Insects (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Soldier"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "2"
"stats":
  - !!int "3"
  - !!int "14"
  - !!int "10"
  - !!int "2"
  - !!int "9"
  - !!int "2"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [flanked](/3-Mechanics/CLI/conditions.md#Flanked), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 10 ft., passive Perception 9"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The swarm has advantage on opportunity attacks, and creatures provoke\
      \ opportunity attacks from the swarm even if they take the Disengage action\
      \ before leaving the swarm's reach."
    "name": "Multitudinous"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny insect. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's\
      \ space. Hit: 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the\
      \ swarm has half their hit points or fewer."
    "name": "Bite"
  - "desc": "If the swarm has at least half their hit points remaining, they emit\
      \ an annoying drone, buzz, or skittering sound. Until the start of the swarm's\
      \ next turn, creatures within 15 feet of the swarm who can hear them have disadvantage\
      \ on attack rolls against creatures other than the swarm."
    "name": "Distracting Buzz"
"source":
  - "FleeMortals"
```
^statblock