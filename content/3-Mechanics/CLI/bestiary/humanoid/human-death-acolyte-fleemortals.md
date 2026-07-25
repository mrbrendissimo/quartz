---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Death Acolyte
---
# [Human Death Acolyte](3-Mechanics\CLI\bestiary\humanoid/human-death-acolyte-fleemortals.md)
*Source: Flee, Mortals! p. 160*  

```statblock
"name": "Human Death Acolyte (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Minion"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "9"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "When an enemy succeeds on a death saving throw while within 30 feet of\
      \ three or more acolytes who aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ the success instead counts as a failure, and if the roll was a 20, the enemy\
      \ doesn't regain hit points."
    "name": "Death Chant"
  - "desc": "When the acolyte makes or joins an attack that's made with advantage,\
      \ the attack deals an extra 1 damage per acolyte who made or joined the attack."
    "name": "Exploit Weakness"
  - "desc": "If the acolyte takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the acolyte takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 2\
      \ necrotic damage, and if this attack was made by more than one acolyte, a creature\
      \ of the acolytes' choice within 30 feet of them regains 1 hit point per acolyte\
      \ who joined this group attack."
    "name": "Transfer Life (Group Attack)"
  - "desc": "Ranged Spell Attack: +4 to hit, range 30 ft., one target. Hit: 2\
      \ necrotic damage."
    "name": "Necrotic Bolt (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock