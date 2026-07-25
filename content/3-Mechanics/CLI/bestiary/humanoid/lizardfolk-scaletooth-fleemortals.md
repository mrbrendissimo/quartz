---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/lizardfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Scaletooth
---
# [Lizardfolk Scaletooth](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-scaletooth-fleemortals.md)
*Source: Flee, Mortals! p. 183*  

```statblock
"name": "Lizardfolk Scaletooth (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Brute"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "15"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+2"
"senses": "passive Perception 10"
"languages": "Common, Draconic"
"cr": "1/2"
"traits":
  - "desc": "The scaletooth can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The scaletooth makes one Bite attack and one Tail attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 4\
      \ (1d4 + 2) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ the scaletooth can move them 5 feet in any direction or grapple them (escape\
      \ DC 12). Until this grapple ends, the scaletooth can't make a Tail attack against\
      \ another target."
    "name": "Tail"
  - "desc": "The scaletooth makes a Bite attack with advantage against one creature\
      \ they have [grappled](/3-Mechanics/CLI/conditions.md#Grappled), dealing an\
      \ extra 3 (d6) piercing damage on a hit."
    "name": "Rending Bite"
"reactions":
  - "desc": "If the scaletooth fails a Strength or Dexterity saving throw, they lose\
      \ their tail and succeed instead. They regrow their tail when they finish a\
      \ long rest."
    "name": "Reptilian Escape (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-scaletooth-fleemortals.png"
```
^statblock