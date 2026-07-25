---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Prince Ellan Farra
---
# [Prince Ellan Farra](3-Mechanics\CLI\bestiary\humanoid/prince-ellan-farra-fleemortals.md)
*Source: Flee, Mortals! p. 383*  

```statblock
"name": "Prince Ellan Farra (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, Controller"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "24"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "24"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "10"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+3"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Elvish"
"cr": "6"
"traits":
  - "desc": "When a creature targets Ellan with an attack, power, or spell, the creature\
      \ must succeed on a DC 18 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by him until the end of his next turn (no action required)."
    "name": "Elf Glamour (1/Day)"
  - "desc": "While he is conscious, Ellan and any allies within 20 feet of him who\
      \ can see him can't be [charmed](/3-Mechanics/CLI/conditions.md#Charmed) or\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)."
    "name": "Resolute Aura"
"actions":
  - "desc": "Ellan makes two Bladed Scepter attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 11\
      \ (1d8 + 7) bludgeoning damage plus 10 (3d6) poison damage, and the target must\
      \ succeed on a DC 18 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Bladed Scepter"
  - "desc": "Ellan speaks a one-word command to up to two creatures he can see within\
      \ 60 feet of him.\n\nEach target must succeed on a DC 18 Wisdom saving throw\
      \ or follow the command on their next turn. The spell has no effect if the target\
      \ is Undead, doesn't understand Common or Elvish, or would be directly harmed\
      \ by following the command. If the target can't follow Ellan's command, the\
      \ spell ends. Some typical commands and their effects follow:\n\n- Approach.\
      \ The target moves toward Ellan by the shortest and most direct route, ending\
      \ their turn if they move within 5 feet of Ellan.  \n- Drop. The target\
      \ drops whatever they are holding and then ends their turn.  \n- Flee. The\
      \ target spends their turn moving away from Ellan by the fastest available means.\
      \  \n- Grovel. The target falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and then ends their turn.  \n- Halt. The target doesn't move and takes\
      \ no actions.  "
    "name": "Command (2nd-Level Spell)"
  - "desc": "Ellan conjures unholy fire around one creature he can see within 60 feet\
      \ of him. The target must make a DC 18 Dexterity saving throw. On a failed save,\
      \ the target takes 27 (6d8) fire damage and is enveloped (save ends at end of\
      \ turn). While enveloped, a creature takes 7 (2d6) fire damage at the start\
      \ of each of their turns. On a successful save, the target takes half as much\
      \ damage and isn't enveloped."
    "name": "Unholy Flame (3rd-Level Spell)"
"source":
  - "FleeMortals"
```
^statblock