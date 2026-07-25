---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/minion
- ttrpg-cli/monster/type/humanoid/time-raider
statblock: inline
statblock-link: "#^statblock"
aliases:
- Time Raider Archon
---
# [Time Raider Archon](3-Mechanics\CLI\bestiary\humanoid/time-raider-archon-fleemortals.md)
*Source: Flee, Mortals! p. 229*  

```statblock
"name": "Time Raider Archon (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "time raider, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "14"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Common, Kuran'zoi"
"cr": "3"
"traits":
  - "desc": "If the archon takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the archon takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "The archon is immune to any effect that would sense their emotions, read\
      \ their thoughts, reveal they are lying, or reveal their alignment or location."
    "name": "Psychic Scar"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 bludgeoning\
      \ damage. If two or more archons joined the attack, the target must succeed\
      \ on a Constitution saving throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn. The DC for this saving throw equals 10 plus\
      \ the number of archons who joined the attack."
    "name": "Brutal Flail (Group Attack)"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. Hit:\
      \ 3 radiant damage."
    "name": "Blaster (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock