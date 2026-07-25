---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental/controller
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/water
statblock: inline
statblock-link: "#^statblock"
aliases:
- Principle of Growth
---
# [Principle of Growth](3-Mechanics\CLI\bestiary\elemental/principle-of-growth-fleemortals.md)
*Source: Flee, Mortals! p. 98*  

```statblock
"name": "Principle of Growth (FleeMortals)"
"size": "Huge"
"type": "elemental"
"subtype": "earth, water, Controller"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d12 + 126"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "11"
  - !!int "25"
  - !!int "11"
  - !!int "16"
  - !!int "14"
"speed": "50 ft., climb 50 ft."
"saves":
  - "strength": !!int "10"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Animal Handling](/3-Mechanics/CLI/skills.md#Animal%20Handling)"
    "desc": "+8"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+10"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+8"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 13"
"languages": "Common, Primordial"
"cr": "15"
"traits":
  - "desc": "The principle regains 20 hit points at the start of their turn if they\
      \ aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated). If they\
      \ take fire damage, they only regain 10 hit points at the start of their next\
      \ turn."
    "name": "Regeneration"
"actions":
  - "desc": "The principle makes two Hampering Roots attacks or two Vernal Lash attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 23\
      \ (4d8 + 5) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 15). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Hampering Roots"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 60 ft., one target. Hit: 27\
      \ (4d10 + 5) slashing damage, and the principle moves the target up to 15 feet\
      \ horizontally."
    "name": "Vernal Lash"
  - "desc": "The principle causes three Large trees with whipping branches to sprout\
      \ from the ground in unoccupied spaces the principle can see within 60 feet\
      \ of them. Each tree has AC 15, 40 hit points, and immunity to psychic damage.\n\
      \nAn enemy who starts their turn within 15 feet of one of these trees must make\
      \ a DC 18 Dexterity saving throw, taking 14 (4d6) slashing damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Burst from the Earth (1/Day)"
"bonus_actions":
  - "desc": "The principle imbues the power of verdancy in themself or another Elemental\
      \ they can see within 30 feet of them, granting one of the following effects\
      \ of that Elemental's choice:\n\n- Roots of the Mind. For 1 minute, the\
      \ Elemental can link with each Large or larger plant object they can see within\
      \ 90 feet of them (no action required). For the duration, the Elemental can\
      \ perceive, make attacks, and use actions as if they were in the space of a\
      \ linked plant.  \n- Thunder Burst. Thorny vines burst from the Elemental.\
      \ Each enemy the Elemental can see within 30 feet of them must make a DC 16\
      \ Dexterity saving throw. On a failed save, a target takes 27 (6d8) piercing\
      \ damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until\
      \ the end of their next turn. On a successful save, they take half as much damage\
      \ and aren't [restrained](/3-Mechanics/CLI/conditions.md#Restrained).  "
    "name": "Convocation of Verdure (2/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/principle-of-growth-fleemortals.png"
```
^statblock