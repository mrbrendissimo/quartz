---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/kobold
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Centurion
---
# [Kobold Centurion](3-Mechanics\CLI\bestiary\humanoid/kobold-centurion-fleemortals.md)
*Source: Flee, Mortals! p. 173*  

```statblock
"name": "Kobold Centurion (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Controller"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "14"
  - !!int "8"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "The centurion gains a +1 bonus to AC while within 5 feet of at least\
      \ one ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the centurion must be wielding a shield."
    "name": "Shield? Shield!"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
    "name": "Pilum"
  - "desc": "The centurion ignites a pilum then uses it to make a ranged Pilum attack\
      \ against a target within 60 feet of them. Hit or miss, the target and each\
      \ creature in a 5-foot-wide line between the target and the centurion must succeed\
      \ on a DC 13 Dexterity saving throw or take 5 (2d4) fire damage. The line smolders\
      \ for 1 minute, creating a 5-foot-wide, 20-foot-tall wall of opaque smoke. A\
      \ creature within reach of the pilum can use an action to extinguish it, causing\
      \ the smoke to dissipate."
    "name": "Firetail Pilum (2/Day)"
  - "desc": "The centurion straps a vial of unstable ores to a pilum then uses it\
      \ to make a ranged Pilum attack against a target within 60 feet of them. Hit\
      \ or miss, the ores explode after the attack. The target and each creature within\
      \ 10 feet of them must make a DC 13 Constitution saving throw. On a failed save,\
      \ a creature takes 7 (2d6) thunder damage, is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ and is [deafened](/3-Mechanics/CLI/conditions.md#Deafened) for 1 minute (save\
      \ ends at end of turn). On a successful save, a creature takes only half as\
      \ much damage and isn't knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ or [deafened](/3-Mechanics/CLI/conditions.md#Deafened)."
    "name": "Boom Pilum!!! (1/Day)"
"source":
  - "FleeMortals"
```
^statblock