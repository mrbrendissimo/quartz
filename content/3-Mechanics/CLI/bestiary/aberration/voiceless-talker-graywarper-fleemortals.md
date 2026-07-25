---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Voiceless Talker Graywarper
---
# [Voiceless Talker Graywarper](3-Mechanics\CLI\bestiary\aberration/voiceless-talker-graywarper-fleemortals.md)
*Source: Flee, Mortals! p. 283*  

```statblock
"name": "Voiceless Talker Graywarper (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Minion"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "12"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "14"
  - !!int "18"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "5"
"traits":
  - "desc": "If the graywarper takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the graywarper takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When a non-minion voiceless talker within 30 feet of the graywarper uses\
      \ telepathy or manifests a psionic power, they can do so as if they were in\
      \ the graywarper's space."
    "name": "Psionic Nexus"
"actions":
  - "desc": "Melee  or Ranged Power Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
      \ one target. Hit: 4 psychic damage. If the target is a creature and if three\
      \ or more graywarpers joined the attack, the target must make a Charisma saving\
      \ throw. The DC for this saving throw is 11 plus the number of graywarpers who\
      \ joined the attack. On a failed save, the target becomes phased until the end\
      \ of their next turn. While phased, the creature is translucent and immaterial,\
      \ and they deal half damage with weapon attacks and unarmed strikes."
    "name": "Phase Chant (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock