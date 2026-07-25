---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghoul Craver
---
# [Ghoul Craver](3-Mechanics\CLI\bestiary\undead/ghoul-craver-fleemortals.md)
*Source: Flee, Mortals! p. 252*  

```statblock
"name": "Ghoul Craver (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "8"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "5"
  - !!int "8"
  - !!int "5"
"speed": "40 ft."
"damage_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "the languages they knew in life"
"cr": "1"
"traits":
  - "desc": "Enemies can't take the Disengage action while three or more cravers are\
      \ within 5 feet of them."
    "name": "Ever So Hungry"
  - "desc": "If the craver takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the craver takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 1\
      \ slashing damage, and the next non-minion ghoul who attacks that target before\
      \ the start of the craver's next turn gains a bonus to the attack roll equal\
      \ to the number of cravers who joined the attack."
    "name": "Just a Taste (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock