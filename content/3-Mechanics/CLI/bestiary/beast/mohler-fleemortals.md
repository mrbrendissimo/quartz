---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mohler
---
# [Mohler](3-Mechanics\CLI\bestiary\beast/mohler-fleemortals.md)
*Source: Flee, Mortals! p. 211*  

```statblock
"name": "Mohler (FleeMortals)"
"size": "Small"
"type": "beast"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "14"
  - !!int "12"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "20 ft., burrow 40 ft."
"senses": "blindsight 20 ft., tremorsense 40 ft., passive Perception 11"
"languages": ""
"cr": "1/4"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) slashing damage."
    "name": "Claw"
  - "desc": "As the mohler burrows under a Large or smaller creature on the ground\
      \ within 5 feet of them, the mohler shifts the ground. The creature above them\
      \ must succeed on a DC 12 Dexterity saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Earth Bump"
  - "desc": "The mohler burrows up to their burrowing speed. Ground within 5 feet\
      \ of where the mohler burrows becomes difficult terrain."
    "name": "Ground Grinder"
"reactions":
  - "desc": "If the mohler fails a Dexterity saving throw while burrowing, they succeed\
      \ instead."
    "name": "Zip"
"source":
  - "FleeMortals"
```
^statblock