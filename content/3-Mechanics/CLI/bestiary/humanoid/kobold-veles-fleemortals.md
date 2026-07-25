---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Veles
---
# [Kobold Veles](3-Mechanics\CLI\bestiary\humanoid/kobold-veles-fleemortals.md)
*Source: Flee, Mortals! p. 176*  

```statblock
"name": "Kobold Veles (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "10"
"hit_dice": "3d6"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "8"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
  - "desc": "The veles gains a +1 bonus to AC while within 5 feet of at least one\
      \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the veles must be wielding a shield."
    "name": "Shield? Shield!"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 4 (1d6 + 1) piercing damage. If the attack hits a\
      \ creature wielding a shield, the veles can embed the pilum in the shield, giving\
      \ the target disadvantage on attack rolls until the target either stops wielding\
      \ the shield or uses an action to remove the pilum from it. The veles carries\
      \ six pila."
    "name": "Pilum"
"bonus_actions":
  - "desc": "The veles moves up to half their speed without provoking opportunity\
      \ attacks."
    "name": "Pivot"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-veles-fleemortals.png"
```
^statblock