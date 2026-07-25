---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/retainer
- ttrpg-cli/monster/type/aberration/voiceless-talker
statblock: inline
statblock-link: "#^statblock"
aliases:
- Voiceless Talker Operative
---
# [Voiceless Talker Operative](3-Mechanics\CLI\bestiary\aberration/voiceless-talker-operative-fleemortals.md)
*Source: Flee, Mortals! p. 288*  

```statblock
"name": "Voiceless Talker Operative (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "voiceless talker, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3 plus PB"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+1 plus PB"
"damage_resistances": "bludgeoning"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Common, Deep Speech, Undercommon, telepathy 60 ft."
"actions":
  - "desc": "Ranged Weapon Attack: +3 plus PB to hit, range 80/320 ft., one target.\
      \ Hit: 1d10 plus PB force damage. Beginning at 7th level, the operative can\
      \ make this attack twice, instead of once, when they take the Attack action\
      \ on their turn."
    "name": "Signature Attack (Psionic Pistol)"
  - "desc": "When the operative hits a creature with a signature attack, they can\
      \ attempt to teleport the target. The target must succeed on a DC 10 plus PB\
      \ Wisdom saving throw or be teleported up to 30 feet to an unoccupied space\
      \ on the ground that the operative can see."
    "name": "3rd Level: Phasing Charge (3/Day)"
  - "desc": "As an action, the operative releases a powerful pulse of energy. Each\
      \ enemy within 10 feet of the operative must make a DC 10 plus PB Strength saving\
      \ throw. On a failed save, a creature takes PBd6 force damage and is pushed\
      \ up to 10 feet directly away from the operative. On a successful save, a creature\
      \ takes half as much damage and isn't pushed."
    "name": "5th Level: Telekinetic Repulsion (3/Day)"
  - "desc": "The operative psionically plunders the mind of a creature they can see\
      \ within 30 feet of them. The target must make a DC 10 plus PB Intelligence\
      \ saving throw. On a failed save, the target takes 22 (4d10) psychic damage,\
      \ and for 1 minute, the target's proficiency bonus is cumulatively lowered by\
      \ 1 and the infiltrator gains a cumulative +1 bonus to attack and damage rolls\
      \ and to each feature's save DC. On a successful save, a target takes half as\
      \ much damage and doesn't have their proficiency bonus reduced.\n\nA creature\
      \ whose proficiency bonus drops to 0 can't form new thoughts or speak, and they\
      \ have disadvantage on ability checks, attack rolls, and saving throws."
    "name": "7th Level: Memory Thief (3/Day; 4th-Order Power; Concentration)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/voiceless-talker-operative-fleemortals.png"
```
^statblock