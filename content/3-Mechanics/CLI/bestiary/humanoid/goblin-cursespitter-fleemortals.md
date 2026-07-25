---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/goblin
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goblin Cursespitter
---
# [Goblin Cursespitter](3-Mechanics\CLI\bestiary\humanoid/goblin-cursespitter-fleemortals.md)
*Source: Flee, Mortals! p. 126*  

```statblock
"name": "Goblin Cursespitter (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Controller"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "15"
"speed": "30 ft., climb 20 ft."
"saves":
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "The cursespitter doesn't provoke opportunity attacks when they move out\
      \ of an enemy's reach."
    "name": "Crafty"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. Hit: 7 (2d6) poison damage, and the target must succeed on a\
      \ DC 12 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Toxic Touch (Cantrip)"
  - "desc": "The cursespitter chooses one creature they can see within 60 feet of\
      \ them. The target's bones are wracked with pain until the end of their next\
      \ turn. The first time the target willingly moves or uses an action, a bonus\
      \ action, or a reaction before then, they must succeed on a DC 12 Constitution\
      \ saving throw or take 9 (2d8) necrotic damage."
    "name": "Brittle Bone Hex (Cantrip)"
  - "desc": "The cursespitter chooses up to two willing creatures they can see within\
      \ 30 feet of them. Each creature is teleported to an unoccupied space within\
      \ 5 feet of the cursespitter."
    "name": "To Me!"
  - "desc": "The cursespitter chooses one creature they can see within 60 feet of\
      \ them. The target must make a DC 12 Wisdom saving throw. On a failed save,\
      \ the target falls [prone](/3-Mechanics/CLI/conditions.md#Prone) and can't stand\
      \ back up for 1 minute (save ends at end of turn)."
    "name": "Dizzying Hex (2/Day; 1st-Level Spell)"
"reactions":
  - "desc": "When a creature the cursespitter can see hits them with an attack, the\
      \ cursespitter chooses a willing ally within 5 feet of them. The attack hits\
      \ the ally instead."
    "name": "Cowardly Commander"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/goblin-cursespitter-fleemortals.webp"
```
^statblock