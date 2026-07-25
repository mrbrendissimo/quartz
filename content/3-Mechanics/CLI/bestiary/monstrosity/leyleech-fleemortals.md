---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Leyleech
---
# [Leyleech](3-Mechanics\CLI\bestiary\monstrosity/leyleech-fleemortals.md)
*Source: Flee, Mortals! p. 341*  

```statblock
"name": "Leyleech (FleeMortals)"
"size": "Small"
"type": "monstrosity"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "13"
  - !!int "4"
  - !!int "12"
  - !!int "8"
"speed": "30 ft."
"condition_immunities": "[prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "The leyleech has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) piercing damage. If the target is a creature who can cast spells, the\
      \ leyleech chooses one of the target's spellcasting abilities. That ability\
      \ score is reduced by 1 (min- imum score of 1) until the target finishes a short\
      \ or long rest, and the leyleech's form becomes charged for 1 minute or until\
      \ they use Magic Purge."
    "name": "Bite"
  - "desc": "The leyleech spews corrupted magical energy at a creature they can see\
      \ within 30 feet of them. The leyleech is no longer charged, and the target\
      \ must make a DC 11 Constitution saving throw, taking 7 (2d6) force damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Magic Purge (Charged Form Only)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/leyleech-fleemortals.png"
```
^statblock