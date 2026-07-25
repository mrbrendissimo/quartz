---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/ogre
- ttrpg-cli/monster/type/giant/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ogre Basher
---
# [Ogre Basher](3-Mechanics\CLI\bestiary\giant/ogre-basher-fleemortals.md)
*Source: Flee, Mortals! p. 199*  

```statblock
"name": "Ogre Basher (FleeMortals)"
"size": "Large"
"type": "giant"
"subtype": "ogre, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
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
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Giant"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 2d4 plus PB piercing damage. Beginning at 7th level, the basher can make this\
      \ attack twice, instead of once, when they take the Attack action on their turn."
    "name": "Signature Attack (Spiked Club)"
  - "desc": "When the basher takes damage from a creature the basher can see within\
      \ 5 feet of them, the basher can use their reaction to instead take no damage\
      \ and make a signature attack against the creature."
    "name": "3rd Level: Angry Denial (3/Day)"
  - "desc": "As an action, the basher grabs a willing Medium or smaller creature they\
      \ can see within 5 feet of them and hurls the creature to an unoccupied space\
      \ within 30 feet of the basher. If the creature lands within 5 feet of an enemy,\
      \ the creature can use a reaction to make a melee attack against that enemy."
    "name": "5th Level: Throw Away (3/Day)"
  - "desc": "As an action, the basher sweeps their spiked club in an enormous circle,\
      \ making a signature attack against each enemy within 10 feet of them. This\
      \ attack has a +PB bonus to its attack and damage rolls, and if it hits a Large\
      \ or smaller creature, the basher can push the target up to 10 feet away from\
      \ them."
    "name": "7th Level: Wide Sweep (3/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/ogre-basher-fleemortals.png"
```
^statblock