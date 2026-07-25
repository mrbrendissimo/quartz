---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swarm of Skitterlings
---
# [Swarm of Skitterlings](3-Mechanics\CLI\bestiary\beast/swarm-of-skitterlings-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 26, Flee, Mortals! p. 129*  

```statblock
"name": "Swarm of Skitterlings (WhereEvilLives)"
"size": "Medium"
"type": "beast"
"subtype": "Soldier"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "36"
"hit_dice": "8d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "3"
  - !!int "12"
  - !!int "5"
"speed": "30 ft., fly 60 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "2"
"traits":
  - "desc": "While the swarm occupies an enemy's space, that creature has disadvantage\
      \ on attack rolls made against any target other than the swarm and takes 3 (d6)\
      \ slashing damage if they attack a creature other than the swarm."
    "name": "In Your Face"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny skitterling. The\
      \ swarm can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 0 ft., one target in the swarm's\
      \ space. Hit: 14 (4d6) slashing damage, or 7 (2d6) slashing damage if the\
      \ swarm has half of their hit points or fewer. The target must succeed on a\
      \ DC 10 Constitution saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the start of their next turn. Creatures who are immune to poison damage\
      \ or the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) condition succeed\
      \ on this saving throw automatically."
    "name": "Claws"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock