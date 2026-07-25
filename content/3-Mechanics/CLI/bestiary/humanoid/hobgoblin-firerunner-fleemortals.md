---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hobgoblin Firerunner
---
# [Hobgoblin Firerunner](3-Mechanics\CLI\bestiary\humanoid/hobgoblin-firerunner-fleemortals.md)
*Source: Flee, Mortals! p. 149*  

```statblock
"name": "Hobgoblin Firerunner (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin, Infernal"
"cr": "4"
"traits":
  - "desc": "The firerunner's long jump is up to 30 feet and their high jump is up\
      \ to 15 feet, with or without a running start. The first time a firerunner lands\
      \ after a jump on their turn, each creature within 5 feet of them takes 3 (d6)\
      \ fire damage."
    "name": "Fiery Leap"
  - "desc": "When the firerunner dies, their corpse unleashes a spray of burning orange\
      \ ichor. Each creature within 5 feet of the firerunner takes 5 fire damage."
    "name": "Infernal Ichor"
"actions":
  - "desc": "The firerunner makes two Fire Scimitar attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) slashing damage plus 7 (2d6) fire damage."
    "name": "Fire Scimitar"
  - "desc": "The firerunner moves up to their speed without provoking opportunity\
      \ attacks. Each creature they come within 5 feet of during this movement must\
      \ make a DC 14 Dexterity saving throw, taking 10 (3d6) fire damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Blaze Sprint (Recharge 5-6)"
"source":
  - "FleeMortals"
```
^statblock