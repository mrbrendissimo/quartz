---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Tiro
---
# [Kobold Tiro](3-Mechanics\CLI\bestiary\humanoid/kobold-tiro-fleemortals.md)
*Source: Flee, Mortals! p. 176*  

```statblock
"name": "Kobold Tiro (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Minion"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "4"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "11"
  - !!int "10"
  - !!int "11"
  - !!int "8"
  - !!int "8"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
  - "desc": "If the tiro takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the tiro takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "The tiro gains a +1 bonus to AC while within 5 feet of at least one ally\
      \ who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the tiro must be wielding a shield."
    "name": "Shield? Shield!"
  - "desc": "When the tiro finishes a long rest, they choose a non-minion creature\
      \ to be their commander. While a tiro who isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone) is within 5 feet of their\
      \ commander, the commander gains a cumulative +1 bonus to AC (maximum bonus\
      \ of +5)."
    "name": "Testudo"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 1 piercing damage."
    "name": "Pugio (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock