---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- War Spider
---
# [War Spider](3-Mechanics\CLI\bestiary\beast/war-spider-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 28, Flee, Mortals! p. 130*  

```statblock
"name": "War Spider (WhereEvilLives)"
"size": "Huge"
"type": "beast"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "73"
"hit_dice": "7d12 + 28"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "40 ft., climb 40 ft."
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
  - "desc": "When the spider dies, a [swarm of spiders](/3-Mechanics/CLI/bestiary/beast/swarm-of-spiders-fleemortals.md)\
      \ bursts forth from their remains and acts on the same initiative count as the\
      \ spider did."
    "name": "Baby Burst"
  - "desc": "An allied rider who jumps off the spider has a long jump of 30 feet and\
      \ a high jump of 15 feet, with or without a running start. If an allied rider\
      \ jumps off the spider, the first melee weapon attack the ally makes on the\
      \ same turn has advantage."
    "name": "Rider Launcher"
  - "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The spider ignores movement restrictions caused by webbing."
    "name": "Web Walker"
  - "desc": "Two Small or Tiny creatures can share a space while riding the spider,\
      \ allowing up to eighteen Small or seventy-two Tiny creatures to ride the spider\
      \ at once."
    "name": "Wide Back"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) piercing damage plus 7 (2d6) poison damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage."
    "name": "Bladed Leg"
  - "desc": "The spider sprays webbing from their abdomen in a 15-foot cube. Each\
      \ creature in that area must succeed on a DC 14 Dexterity saving throw or be\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by the webbing. A\
      \ creature can use their action to make a DC 14 Strength or Dexterity check,\
      \ freeing themself or another creature they can reach on a success."
    "name": "Web Spray"
  - "desc": "The spider can move up to their speed and move through the spaces of\
      \ other creatures as if they were difficult terrain. The spider can make one\
      \ Bladed Leg attack against each creature whose space they move into during\
      \ the move. A creature hit by this attack can't take reactions until the start\
      \ of their next turn."
    "name": "Trample (Recharge 6)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/war-spider-fleemortals.webp"
```
^statblock