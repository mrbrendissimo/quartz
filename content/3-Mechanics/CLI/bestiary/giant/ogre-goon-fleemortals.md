---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ogre Goon
---
# [Ogre Goon](3-Mechanics\CLI\bestiary\giant/ogre-goon-fleemortals.md)
*Source: Flee, Mortals! p. 198*  

```statblock
"name": "Ogre Goon (FleeMortals)"
"size": "Large"
"type": "giant"
"subtype": "Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "11"
"hp": !!int "9"
"modifier": !!int "-1"
"stats":
  - !!int "15"
  - !!int "8"
  - !!int "15"
  - !!int "7"
  - !!int "10"
  - !!int "7"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Giant"
"cr": "2"
"traits":
  - "desc": "If the goon takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the goon takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 2 bludgeoning\
      \ damage, and if this attack was made by more than one goon, the target must\
      \ succeed on a Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and moved up to 10 feet horizontally. The DC for this saving throw equals\
      \ 10 plus the number of goons who joined the attack."
    "name": "Fist (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock