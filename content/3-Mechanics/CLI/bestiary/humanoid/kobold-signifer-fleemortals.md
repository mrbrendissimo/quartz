---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Signifer
---
# [Kobold Signifer](3-Mechanics\CLI\bestiary\humanoid/kobold-signifer-fleemortals.md)
*Source: Flee, Mortals! p. 175*  

```statblock
"name": "Kobold Signifer (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Support"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "17"
"hit_dice": "5d6"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "10"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "The signifer gains a +1 bonus to AC while within 5 feet of at least one\
      \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the signifer must be wielding a shield."
    "name": "Shield? Shield!"
  - "desc": "Each kobold unit can have one or more signifers, whose weapon is their\
      \ unit's battle standard. If a signifer drops their signum, they use the kobold\
      \ tiro stat block instead. If an allied kobold tiro uses an action to pick up\
      \ a signum not carried by another creature, that tiro uses the kobold signifer\
      \ stat block instead. When a signifer or tiro's stat block changes in this way,\
      \ any conditions or effects currently affecting them remain active, and their\
      \ hit points and hit point maximum remain the same.\n\nA signum that isn't being\
      \ held by a creature can be damaged; it has AC 15, 5 hit points, and immunity\
      \ to poison and psychic damage."
    "name": "Standard Bearer"
"actions":
  - "desc": "The signifer makes two Signum attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) bludgeoning damage."
    "name": "Signum"
  - "desc": "The signifer chooses up to four kobolds within 60 feet of them who can\
      \ hear them. Each kobold can use their reaction to move up to their speed, and\
      \ each kobold who does so must end this movement within 5 feet of an ally."
    "name": "Shield Wall Formation"
"bonus_actions":
  - "desc": "The signifer and each ally within 30 feet of them who can hear them regains\
      \ 5 (2d4) hit points."
    "name": "Glory to the Legion (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-signifer-fleemortals.png"
```
^statblock