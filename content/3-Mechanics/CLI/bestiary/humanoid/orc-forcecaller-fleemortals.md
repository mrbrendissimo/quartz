---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/minion
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Forcecaller
---
# [Orc Forcecaller](3-Mechanics\CLI\bestiary\humanoid/orc-forcecaller-fleemortals.md)
*Source: Flee, Mortals! p. 207*  

```statblock
"name": "Orc Forcecaller (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Minion"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "8"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "15"
"speed": "35 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1"
"traits":
  - "desc": "If the forcecaller takes damage from an attack or as the result of a\
      \ failed saving throw, their hit points are reduced to 0. If the forcecaller\
      \ takes damage from another effect, they die if the damage equals or exceeds\
      \ their hit point maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When the forcecaller is reduced to 0 hit points while they aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ they can deal 1 force damage to an enemy within 5 feet of them."
    "name": "Relentless Minion"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 30/60\
      \ ft., one target. Hit: 1 force damage. If two or more forcecallers joined\
      \ the attack, they can deal the same amount of force damage to another creature\
      \ within 10 feet of the target."
    "name": "Chainspoken (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock