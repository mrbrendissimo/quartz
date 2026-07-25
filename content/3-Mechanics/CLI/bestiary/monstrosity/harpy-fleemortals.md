---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Harpy
---
# [Harpy](3-Mechanics\CLI\bestiary\monstrosity/harpy-fleemortals.md)
*Source: Flee, Mortals! p. 142*  

```statblock
"name": "Harpy (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Controller"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "7"
  - !!int "10"
  - !!int "14"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "Common, Giant"
"cr": "1"
"traits":
  - "desc": "The harpy can't use their blindsight while [deafened](/3-Mechanics/CLI/conditions.md#Deafened)."
    "name": "Echolocation"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (3d4\
      \ + 2) slashing damage. If the target is a Medium or smaller creature [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the harpy, they are also [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 12). Until this grapple ends, the harpy can't use their Talons\
      \ attack on another target."
    "name": "Talons"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
      \ 7 (2d4 + 2) bludgeoning damage."
    "name": "Rock"
  - "desc": "The harpy starts singing a beautiful song. They continue singing until\
      \ they choose to stop (no action required) or until they become [deafened](/3-Mechanics/CLI/conditions.md#Deafened)\
      \ or [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated). When a non-harpy\
      \ creature starts their turn within 200 feet of the singing harpy, if that creature\
      \ shares a language with the harpy and can hear them, that creature must succeed\
      \ on a DC 12 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by the harpy until the harpy stops singing or the target can't hear them anymore.\n\
      \nWhile [charmed](/3-Mechanics/CLI/conditions.md#Charmed) in this way, the target\
      \ can't willingly move on their turn, and they can't attack, damage, or target\
      \ any unwilling harpy with any effect. If the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ target takes damage from a source other than a harpy, they can repeat the\
      \ saving throw, ending the effect on a success.\n\nA creature who succeeds on\
      \ a saving throw to resist or end this effect is immune to the Alluring Song\
      \ of all harpies for 1 hour."
    "name": "Alluring Song"
"bonus_actions":
  - "desc": "The harpy chooses any number of creatures [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by their Alluring Song. Each target must use their reaction, if available,\
      \ to move up to their speed in a direction chosen by the harpy. If this movement\
      \ would lead the target into hazardous terrain, they can make a DC 12 Wisdom\
      \ saving throw before moving. On a successful save, the target's reaction is\
      \ not used and they are no longer [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by Alluring Song."
    "name": "Beckon"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/harpy-fleemortals.png"
```
^statblock