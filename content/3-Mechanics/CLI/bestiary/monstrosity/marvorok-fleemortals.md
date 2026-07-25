---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Marvorok
---
# [Marvorok](3-Mechanics\CLI\bestiary\monstrosity/marvorok-fleemortals.md)
*Source: Flee, Mortals! p. 342*  

```statblock
"name": "Marvorok (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Ambusher"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d10 + 120"
"modifier": !!int "6"
"stats":
  - !!int "17"
  - !!int "23"
  - !!int "23"
  - !!int "10"
  - !!int "18"
  - !!int "12"
"speed": "40 ft., climb 40 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "12"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+16"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+12"
"senses": "blindsight 300 ft., passive Perception 26"
"languages": "Deep Speech"
"cr": "17"
"traits":
  - "desc": "The marvorok can't use their blindsight if they can't breathe or smell."
    "name": "Scent Reliance"
"actions":
  - "desc": "The marvorok makes three Claw attacks and one Eviscerate attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 19\
      \ (3d8 + 6) slashing damage, and if the target is Large or smaller, they are\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 17). Until\
      \ this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ The marvorok can grapple up to two creatures at a time."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the marvorok. Hit: 17 (2d10 + 6) piercing damage plus 17 (2d10 + 6) slashing\
      \ damage."
    "name": "Eviscerate"
"bonus_actions":
  - "desc": "The marvorok makes a Wisdom (Perception) check."
    "name": "Taste the Air"
  - "desc": "The marvorok teleports, along with any creatures they are grappling,\
      \ up to 30 feet to an unoccupied space they can see. If the marvorok teleports\
      \ into an area of dim light or darkness, they can take the Hide action as part\
      \ of this bonus action, and any creatures they are grappling can't speak or\
      \ make noise until the end of the marvorok's next turn."
    "name": "Underground Stalker"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/marvorok-fleemortals.png"
```
^statblock