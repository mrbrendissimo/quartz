---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kingfissure Worm
---
# [Kingfissure Worm](3-Mechanics\CLI\bestiary\monstrosity/kingfissure-worm-fleemortals.md)
*Source: Flee, Mortals! p. 168*  

```statblock
"name": "Kingfissure Worm (FleeMortals)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "Solo"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "297"
"hit_dice": "18d20 + 108"
"modifier": !!int "0"
"stats":
  - !!int "29"
  - !!int "10"
  - !!int "23"
  - !!int "1"
  - !!int "10"
  - !!int "5"
"speed": "60 ft., burrow 50 ft."
"saves":
  - "constitution": !!int "11"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 30 ft., tremorsense 120 ft., passive Perception 10"
"languages": ""
"cr": "15"
"traits":
  - "desc": "The worm has three tongues, each of which can be targeted with attacks\
      \ (AC 20, immunity to psychic damage) while that tongue is grappling a creature.\
      \ When a tongue takes 35 damage or more in a single turn, that tongue is destroyed,\
      \ releasing any target it was grappling. The worm can't use a destroyed tongue\
      \ with their Multiattack or Tongue Grab action until they finish a long rest.\
      \ Damaging or destroying a tongue deals no damage to the worm."
    "name": "Multiple Tongues"
  - "desc": "When the worm fails a saving throw, they can choose to succeed instead.\
      \ When they do, their speed and the reach of their Tongue Grab attack are each\
      \ reduced by a cumulative 10 feet until they finish a long rest. The worm's\
      \ speed and reach can't be reduced below 5 feet in this way."
    "name": "Slowed, Not Stopped (3/Day)"
  - "desc": "The worm can burrow through solid rock at half their burrowing speed\
      \ and leaves a 10-foot-diameter tunnel in their wake."
    "name": "Tunneler"
"actions":
  - "desc": "The worm can make a number of Tongue Grab attacks equal to the number\
      \ of tongues they currently have (see Multiple Tongues). The worm can replace\
      \ any number of those attacks with a use of Swallow."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 30 ft., one target. Hit: 14\
      \ (4d6) acid damage, and the creature is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 19). Until this grapple ends, the worm can't use this tongue against\
      \ another target."
    "name": "Tongue Grab"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 22\
      \ (3d8 + 9) piercing damage. If the target is Huge or smaller, they must succeed\
      \ on a DC 19 Dexterity saving throw or be swallowed (as if by the worm's Swallow\
      \ action)."
    "name": "Maw"
  - "desc": "The worm pulls a Huge or smaller [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ creature into their maw and swallows them. A swallowed creature is no longer\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), but they are [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained), have total cover\
      \ against attacks and other effects outside the worm, and take 28 (8d6) acid\
      \ damage at the start of each of the worm's turns.\n\nIf the worm takes 30 damage\
      \ or more on a single turn from a creature inside them, the worm must succeed\
      \ on a DC 21 Constitution check at the end of that turn or regurgitate all swallowed\
      \ creatures, each of whom fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ in an unoccupied space within 10 feet of the worm. If the worm dies, a swallowed\
      \ creature can escape from the corpse by using 20 feet of movement, exiting\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Swallow"
"bonus_actions":
  - "desc": "The worm violently swings a creature they have [grappled](/3-Mechanics/CLI/conditions.md#Grappled).\
      \ The [grappled](/3-Mechanics/CLI/conditions.md#Grappled) creature takes 10\
      \ (3d6) bludgeoning damage, and each enemy within 10 feet of the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ creature must succeed on a DC 16 Dexterity saving throw or take 10 (3d6) bludgeoning\
      \ damage."
    "name": "Tongue Sweep"
"reactions":
  - "desc": "When one of the worm's tongues takes damage that doesn't immediately\
      \ destroy it, the worm can release any target that tongue is grappling and recall\
      \ the tongue back inside the worm's body. That tongue can't be targeted until\
      \ the worm uses it to grapple a creature again."
    "name": "Tongue Recall"
"legendary_actions":
  - "desc": "The worm has three villain actions. They can take each action once during\
      \ an encounter after an enemy's turn. They can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "The worm writhes, sending tremors through the ground and opening a 20-foot-wide,\
      \ 100-foot-long, 40-foot-deep fissure in the ground, originating from the worm.\
      \ Each creature in that area must make a DC 19 Dexterity saving throw. On a\
      \ failed save, a creature falls into the fissure, taking 14 (4d6) bludgeoning\
      \ damage from the fall and landing [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, a creature flees to the closest unoccupied space outside\
      \ the fissure's area."
    "name": "Action 1: Open the Earth"
  - "desc": "The worm burrows up to half their speed and then bursts through the surface,\
      \ breaching the ground in a 10-foot-radius circle. Huge and smaller creatures\
      \ within that area must succeed on a DC 19 Dexterity saving throw or be swallowed\
      \ (as if by the worm's Swallow action)."
    "name": "Action 2: Earth Breach"
  - "desc": "The worm projectile vomits the contents of their stomach in a 60-foot\
      \ cone. Each creature in that area must make a DC 19 Dexterity saving throw,\
      \ taking 21 (6d6) bludgeoning damage plus 21 (6d6) acid damage on a failed save,\
      \ or half as much damage on a successful one. Additionally, creatures who were\
      \ swallowed by the worm are regurgitated, taking 21 (6d6) bludgeoning damage\
      \ and landing [prone](/3-Mechanics/CLI/conditions.md#Prone) in an unoccupied\
      \ space of the worm's choice within that area."
    "name": "Action 3: Better Out Than In"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/kingfissure-worm-fleemortals.png"
```
^statblock