---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swarm of Spiders
---
# [Swarm of Spiders](3-Mechanics\CLI\bestiary\beast/swarm-of-spiders-fleemortals.md)
*Source: Flee, Mortals! p. 42*  

```statblock
"name": "Swarm of Spiders (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Controller"
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
"senses": "blindsight 10 ft., darkvision 30 ft., passive Perception 9"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The swarm can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny spider. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
  - "desc": "The swarm ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's\
      \ space. Hit: 5 (2d4) piercing damage plus 4 (d8) poison damage, or 2 (d4)\
      \ piercing damage plus 3 (d6) poison damage if the swarm has half their hit\
      \ points or fewer."
    "name": "Bite"
  - "desc": "The swarm mobs a creature in their space and attaches to them. When the\
      \ swarm takes damage other than psychic damage, the attached creature also takes\
      \ half as much damage. The attached creature has disadvantage on attacks against\
      \ creatures other than the swarm, and attacks against the attached creature\
      \ have advantage.\n\nWhile attached, the swarm can't attack another target.\
      \ The attached creature or another creature who can reach them can shake off\
      \ the swarm and detach them as an action. The swarm can detach by spending 5\
      \ feet of their movement."
    "name": "Too Many Legs"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/swarm-of-spiders-whereevillives.png"
```
^statblock