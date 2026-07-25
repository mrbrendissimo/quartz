---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Owlbear
---
# [Owlbear](3-Mechanics\CLI\bestiary\monstrosity/owlbear-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 108, Flee, Mortals! p. 222*  

```statblock
"name": "Owlbear (WhereEvilLives)"
"size": "Large"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d10 + 22"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "12"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The owlbear's long jump is up to 30 feet and their high jump is 15 feet,\
      \ with or without a running start. If the owlbear leaps at least 20 feet toward\
      \ a target and then hits them with a Bite or Claw attack, the target must succeed\
      \ on a DC 15 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Deadly Leap"
  - "desc": "The owlbear has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on sight or smell."
    "name": "Keen Sight and Smell"
"actions":
  - "desc": "The owlbear makes one Bite and one Claw attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 11\
      \ (1d12 + 5) piercing damage, and the owlbear can move the target 5 feet in\
      \ any direction."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d6 + 5) slashing damage."
    "name": "Claw"
  - "desc": "The owlbear attempts to grab and crush a creature they can see within\
      \ 5 feet of them. The target must make a DC 15 Dexterity saving throw. On a\
      \ failed save, the target takes 22 (4d10) bludgeoning damage and is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 15). On a successful save, the target takes half as much damage\
      \ and is not [grappled](/3-Mechanics/CLI/conditions.md#Grappled). Until this\
      \ grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and takes 5 (d10) bludgeoning damage at the start of each of their turns.\
      \ The grapple ends if the owlbear uses Bear Hug on another target or makes a\
      \ Claw attack against another target."
    "name": "Bear Hug (Recharge 4-6)"
"reactions":
  - "desc": "When the owlbear takes damage, they can move up to half their speed without\
      \ provoking opportunity attacks."
    "name": "Hulking Rush"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/owlbear-whereevillives.png"
```
^statblock