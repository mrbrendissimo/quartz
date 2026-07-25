---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ice Spider Queen
---
# [Ice Spider Queen](3-Mechanics\CLI\bestiary\beast/ice-spider-queen-skt.md)
*Source: Storm King's Thunder p. 128*  

```statblock
"name": "Ice Spider Queen (SKT)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "4d10 + 4"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "2"
  - !!int "11"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "2"
"traits":
  - "desc": "Any creature that starts its turn within 5 feet of the spider takes 5\
      \ (2d4) cold damage."
    "name": "Cold Aura"
  - "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "While in contact with a web, the spider knows the exact location of any\
      \ other creature in contact with the same web."
    "name": "Web Sense"
  - "desc": "The spider ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7\
      \ (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving\
      \ throw, taking 9 (2d8) poison damage on a failed save, or half as much damage\
      \ on a successful one. If the poison damage reduces the target to 0 hit points,\
      \ the target is stable but [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 hour, even after regaining hit points, and is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ while [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) in this way."
    "name": "Bite"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one creature. Hit:\
      \ The target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by webbing,\
      \ and takes 2 (d4) cold damage at the start of each of its turns. As an action,\
      \ the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) target can make\
      \ a DC 12 Strength check, bursting the webbing on a success. The webbing can\
      \ also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage;\
      \ immunity to poison, and psychic damage)."
    "name": "Icy Web (Recharge 5-6)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/beast/token/ice-spider-queen-skt.webp"
```
^statblock