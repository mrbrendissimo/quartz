---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Terrorsaur
---
# [Lizardfolk Terrorsaur](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-terrorsaur-fleemortals.md)
*Source: Flee, Mortals! p. 184*  

```statblock
"name": "Lizardfolk Terrorsaur (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor; 16 while flying"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "16"
"speed": "30 ft., fly 50 ft., swim 30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "Common, Draconic"
"cr": "4"
"traits":
  - "desc": "While the terrorsaur is flying, their AC is 16."
    "name": "Aerial Agility"
  - "desc": "The terrorsaur can breathe air and water."
    "name": "Amphibious"
  - "desc": "The terrorsaur can use only their flying speed if they first either fall\
      \ 10 feet without hitting the ground or walk 10 feet in a straight line on that\
      \ turn."
    "name": "Running Start"
"actions":
  - "desc": "The terrorsaur makes one Bite attack and one Glaive attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9\
      \ (1d10 + 4) slashing damage."
    "name": "Glaive"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 30/120 ft., one creature. Hit:\
      \ 1 piercing damage plus 17 (5d6) poison damage, and the target must succeed\
      \ on a DC 13 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Blowgun (Recharge 6)"
"reactions":
  - "desc": "If the terrorsaur fails a Strength or Dexterity saving throw, they lose\
      \ their tail and succeed instead. They regrow their tail when they finish a\
      \ long rest."
    "name": "Reptilian Escape (1/Day)"
  - "desc": "If the terrorsaur takes damage from a melee attack, they can move up\
      \ to half their speed."
    "name": "Skulking Retreat"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-terrorsaur-fleemortals.png"
```
^statblock