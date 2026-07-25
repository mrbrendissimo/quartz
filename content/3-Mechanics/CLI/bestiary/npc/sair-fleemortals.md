---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sair
---
# [Sair](3-Mechanics\CLI\bestiary\npc/sair-fleemortals.md)
*Source: Flee, Mortals! p. 359*  

```statblock
"name": "Sair (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Artillery"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, telepathy 120 ft."
"cr": "2"
"traits":
  - "desc": "Sair doesn't provoke opportunity attacks when they fly out of an enemy's\
      \ reach."
    "name": "Flyby"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claws"
  - "desc": "Ranged Power Attack: +6 to hit, range 120 ft., one target. Hit: 10\
      \ (3d6) psychic damage. If the target is Large or smaller, they are pushed 5\
      \ feet away from Sair."
    "name": "Psionic Bolt (1st-Order Power)"
  - "desc": "Sair psionically pierces the mind of each enemy within 30 feet of them.\
      \ Each target must make a DC 14 Intelligence saving throw, taking 17 (5d6) psychic\
      \ damage on a failed save, or half as much damage on a successful one. A creature\
      \ reduced to 0 hit points by this damage is automatically stabilized."
    "name": "*Mind Scream (1/Day; 3rd-Order Power)"
"source":
  - "FleeMortals"
```
^statblock