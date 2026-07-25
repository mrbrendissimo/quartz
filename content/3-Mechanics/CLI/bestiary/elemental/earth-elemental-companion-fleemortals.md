---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Earth Elemental Companion
---
# [Earth Elemental Companion](3-Mechanics\CLI\bestiary\elemental/earth-elemental-companion-fleemortals.md)
*Source: Flee, Mortals! p. 103*  

```statblock
"name": "Earth Elemental Companion (FleeMortals)"
"size": "Large"
"type": "elemental"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "15 plus PB (natural armor)"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "15"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., burrow 30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
"damage_immunities": "poison"
"condition_immunities": "[petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 10"
"languages": ""
"traits":
  - "desc": "The elemental can burrow through mundane, unworked earth and stone. While\
      \ doing so, the elemental doesn't disturb the material they move through. While\
      \ they use Earth Glide, the elemental can't be used as a mount."
    "name": "Earth Glide"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB bludgeoning damage."
    "name": "Signature Attack (Slam)"
  - "desc": "The elemental makes a signature attack with a reach of 10 feet. On a\
      \ hit, the attack deals an extra PB damage, and the elemental can pull the target\
      \ 5 feet toward them."
    "name": "1st Level: Stretch Attack (2 Ferocity)"
  - "desc": "The elemental strikes the ground, and each creature within 10 feet of\
      \ them must succeed on a DC 10 plus PB Dexterity saving throw or be knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone). The elemental's caregiver automatically\
      \ succeeds on this saving throw."
    "name": "3rd Level: Earthshaker (5 Ferocity)"
  - "desc": "The elemental picks a 10-foot-square area of ground they can see within\
      \ 30 feet of them. Each creature standing in the area must succeed on a DC 10\
      \ plus PB Strength saving throw or partially sink into the ground and become\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained). A creature can use\
      \ their action to make a DC 10 plus PB Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check, freeing themself or another creature within their reach on a success\
      \ and ending the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition\
      \ for the freed creature."
    "name": "5th Level: Transmute Ground (8 Ferocity)"
"bonus_actions":
  - "desc": "While the elemental is within 5 feet of their caregiver, they can hurl\
      \ the caregiver 5 × PB feet in any direction, including up. If the caregiver\
      \ would normally take damage from a fall after being thrown, they can negate\
      \ the damage with a successful DC 15 Dexterity saving throw."
    "name": "Toss Me"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/earth-elemental-companion-fleemortals.png"
```
^statblock