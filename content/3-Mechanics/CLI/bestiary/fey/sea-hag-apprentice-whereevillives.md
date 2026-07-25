---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/hag
- ttrpg-cli/monster/type/fey/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sea Hag Apprentice
---
# [Sea Hag Apprentice](3-Mechanics\CLI\bestiary\fey/sea-hag-apprentice-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 67, Flee, Mortals! p. 141*  

```statblock
"name": "Sea Hag Apprentice (WhereEvilLives)"
"size": "Medium"
"type": "fey"
"subtype": "hag, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "16"
"speed": "30 ft., swim 30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+3 plus PB"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3 plus PB"
"damage_resistances": "cold, lightning"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Aquan, Common, Sylvan"
"traits":
  - "desc": "The apprentice can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +3 plus PB to hit, reach 5 ft. or range\
      \ 60 ft., one target. Hit: 4 (d8) lightning damage. This spell's damage increases\
      \ by d8 when the apprentice reaches 5th level (2d8), 11th level (3d8), and 17th\
      \ level (4d8)."
    "name": "Signature Attack (Zap)"
  - "desc": "As a bonus action, the apprentice rides a crashing wave. They make a\
      \ signature attack against an enemy within 5 feet of them and move up to their\
      \ walking speed without provoking opportunity attacks. If the attack hits, it\
      \ deals an extra PB bludgeoning damage."
    "name": "3rd Level: Wash Away (3/Day)"
  - "desc": "As an action, the apprentice supercharges their foe's nervous system.\
      \ The apprentice makes a signature attack, and if it deals damage to a creature,\
      \ the target must make a DC 10 plus PB Constitution saving throw. On a failed\
      \ save, the target is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and their speed is halved until the end of their next turn."
    "name": "5th Level: Ride the Lightning (3/Day)"
  - "desc": "As an action, the apprentice chooses three creatures the apprentice can\
      \ see within 60 feet of them. Each target feels as though their lungs are filling\
      \ with water and must make a DC 10 plus PB Constitution saving throw. A creature\
      \ who can breathe water or who doesn't need air automatically succeeds on this\
      \ saving throw. On a failed save, a target takes PBd8 force damage, and for\
      \ 1 minute, they can't speak, their speed is halved, and they are [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ (save ends at end of turn). On a successful save, the target takes half as\
      \ much damage and suffers no other effect. Another creature within 5 feet of\
      \ a target can use their action to make a DC 10 plus PB Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ or Intelligence ([Medicine](/3-Mechanics/CLI/skills.md#Medicine)) check, ending\
      \ the effect on a success."
    "name": "7th Level: Drown (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fey/token/sea-hag-apprentice-whereevillives.png"
```
^statblock