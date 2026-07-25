---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crawling Claw Companion
---
# [Crawling Claw Companion](3-Mechanics\CLI\bestiary\undead/crawling-claw-companion-fleemortals.md)
*Source: Flee, Mortals! p. 257*  

```statblock
"name": "Crawling Claw Companion (FleeMortals)"
"size": "Tiny"
"type": "undead"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "5"
  - !!int "12"
  - !!int "8"
"speed": "30 ft., climb 30 ft."
"saves":
  - "name": "Dexterity"
    "desc": "+3 plus PB"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3 plus PB"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+3 plus PB"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 11"
"languages": ""
"traits":
  - "desc": "While the claw is holding an object, their speed is halved. If the claw\
      \ is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone), they drop anything\
      \ they are holding."
    "name": "Fingers for Feet"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB slashing damage."
    "name": "Signature Attack (Claw)"
  - "desc": "The claw makes a signature attack. On a hit, the attack deals an extra\
      \ PB slashing damage, and the claw takes a random object (determined by the\
      \ GM) from an easily accessed pocket, pouch, backpack, or similar container\
      \ the target is wearing or carrying."
    "name": "1st Level: Thieving Attack (2 Ferocity)"
  - "desc": "The claw makes a signature attack. On a hit, the attack deals an extra\
      \ PB slashing damage, and the target must succeed on a DC 10 plus PB Constitution\
      \ saving throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until the\
      \ start of the claw's next turn."
    "name": "3rd Level: Dazing Slash (5 Ferocity)"
  - "desc": "The claw scratches a creature they can see within 5 feet of them. The\
      \ target must make a DC 10 plus PB Constitution saving throw. On a failed save,\
      \ the target takes PBd8 poison damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of the claw's next turn. While [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ in this way, the target can't regain hit points. On a successful save, the\
      \ target takes half as much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)."
    "name": "5th Level: Filthy Scratch (8 Ferocity)"
"bonus_actions":
  - "desc": "The claw moves up to their speed toward the caregiver without provoking\
      \ opportunity attacks. The claw can take the Use an Object action once during\
      \ this movement."
    "name": "Fast Hand (3/Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/crawling-claw-companion-fleemortals.png"
```
^statblock