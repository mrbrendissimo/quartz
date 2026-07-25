---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hellhound Cur
---
# [Hellhound Cur](3-Mechanics\CLI\bestiary\fiend/hellhound-cur-fleemortals.md)
*Source: Flee, Mortals! p. 145*  

```statblock
"name": "Hellhound Cur (FleeMortals)"
"size": "Small"
"type": "fiend"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "10"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "19"
  - !!int "11"
  - !!int "8"
  - !!int "10"
"speed": "30 ft."
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Common and Infernal but can't speak"
"cr": "3"
"traits":
  - "desc": "If a creature starts their turn within 10 feet of two or more curs, that\
      \ creature takes 4 fire damage."
    "name": "Crossfire"
  - "desc": "If the cur takes damage from an attack or as the result of a failed saving\
      \ throw, their hit points are reduced to 0. If the cur takes damage from another\
      \ effect, they die if the damage equals or exceeds their hit point maximum;\
      \ otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 3 fire\
      \ damage, and if the target isn't a hellhound and the attack was made by more\
      \ than one cur, the target must make a Dexterity saving throw with a DC equal\
      \ to 10 plus the number of curs who joined the attack. On a failed save, the\
      \ target is lit on fire for 1 minute (save ends at end of turn), or until the\
      \ target or another creature who can reach them uses an action to extinguish\
      \ the flames. A creature who is on fire at the start of their turn takes fire\
      \ damage equal to the number of curs who joined the attack. If a creature who\
      \ is already on fire is set on fire again on a subsequent turn, the damage isn't\
      \ cumulative, but the duration of the fire resets to 1 minute."
    "name": "Hellish Bite (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock