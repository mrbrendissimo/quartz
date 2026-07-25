---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/retainer
- ttrpg-cli/monster/type/plant/treant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Treant Immobilizer
---
# [Treant Immobilizer](3-Mechanics\CLI\bestiary\plant/treant-immobilizer-fleemortals.md)
*Source: Flee, Mortals! p. 241*  

```statblock
"name": "Treant Immobilizer (FleeMortals)"
"size": "Large"
"type": "plant"
"subtype": "treant, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "12"
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
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+0 plus PB"
"senses": "passive Perception 12"
"languages": "Common, Druidic, Sylvan"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 2d6 plus PB slashing damage. Beginning at 7th level, the immobilizer can make\
      \ this attack twice, instead of once, when they take the Attack action on their\
      \ turn."
    "name": "Signature Attack (Claw)"
  - "desc": "As a bonus action, the immobilizer whips a vine toward a creature they\
      \ can see within 30 feet of them. The target must succeed on a DC 10 plus PB\
      \ Strength saving throw or be pulled up to 10 feet toward the immobilizer and\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 10 plus PB).\
      \ Until this grapple ends, the immobilizer's attacks against the target deal\
      \ an extra PB bludgeoning damage."
    "name": "3rd Level: Lash Out (3/Day)"
  - "desc": "As an action, the im - mobilizer stomps the ground. Each creature within\
      \ 10 feet of the immobilizer must succeed on a DC 10 plus PB Dexterity saving\
      \ throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone). Then the\
      \ immobilizer can make a signature attack with a reach of 10 feet against one\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone) creature."
    "name": "5th Level: Ground Stomp (3/Day)"
  - "desc": "As a bonus action, the immobilizer calls spiky vines to surround a creature\
      \ they can see within 60 feet of them. The target must make a DC 10 plus PB\
      \ Dexterity saving throw. On a failed save, the target takes PBd10 piercing\
      \ damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained). While\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) in this way, the target\
      \ is [blinded](/3-Mechanics/CLI/conditions.md#Blinded). On a successful save,\
      \ the target takes only half damage and isn't [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\n\
      \nA creature can use their action to make a DC 10 plus PB Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ or Dexterity ([Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)) check,\
      \ freeing themself or another creature within reach on a success."
    "name": "7th Level: Entomb (1/Day)"
"source":
  - "FleeMortals"
```
^statblock