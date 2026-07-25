---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hellhound Companion
---
# [Hellhound Companion](3-Mechanics\CLI\bestiary\fiend/hellhound-companion-fleemortals.md)
*Source: Flee, Mortals! p. 145*  

```statblock
"name": "Hellhound Companion (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "50 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "The hound's caregiver can talk to the hound about a specific course of\
      \ action that the caregiver plans to take within the next 30 minutes, tapping\
      \ into divinatory power through the hound's connection to the infernal realm.\
      \ After 1 minute, the hound then gives a response based on its own objective\
      \ prophetic sense of the outcome: one bark for good results, two barks for bad\
      \ results, three barks for both good and bad results, and no barks for results\
      \ that aren't especially good or bad."
    "name": "Consult Hell (Recharges after a Long Rest)"
  - "desc": "The hound has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Bite (Signature Attack)"
  - "desc": "The hound makes a signature attack. On a hit, the attack deals an extra\
      \ PB damage, and the hound can choose another creature within 5 feet of the\
      \ target, dealing PB fire damage to that creature."
    "name": "1st Level: Lava Spittle (2 Ferocity)"
  - "desc": "The hound can move up to their speed without provoking opportunity attacks.\
      \ During or at the end of this move, they can make a signature attack against\
      \ one target within reach."
    "name": "3rd Level: Brutal Charge (5 Ferocity)"
  - "desc": "The hound exhales fire in a 15-foot cone. Each creature in that area\
      \ must make a DC 10 plus PB Dexterity saving throw, taking PBd6 fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "5th Level: Fire Breath (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/hellhound-companion-fleemortals.png"
```
^statblock