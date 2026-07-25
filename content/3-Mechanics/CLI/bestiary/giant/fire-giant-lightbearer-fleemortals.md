---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fire Giant Lightbearer
---
# [Fire Giant Lightbearer](3-Mechanics\CLI\bestiary\giant/fire-giant-lightbearer-fleemortals.md)
*Source: Flee, Mortals! p. 105*  

```statblock
"name": "Fire Giant Lightbearer (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Support"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "137"
"hit_dice": "11d12 + 66"
"modifier": !!int "3"
"stats":
  - !!int "22"
  - !!int "16"
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "13"
"speed": "40 ft."
"saves":
  - "strength": !!int "10"
  - "dexterity": !!int "7"
  - "constitution": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_immunities": "fire"
"senses": "passive Perception 19"
"languages": "Giant"
"cr": "10"
"traits":
  - "desc": "When the lightbearer targets a fire giant with an attack, spell, or other\
      \ supernatural effect that deals fire damage, that target instead regains a\
      \ number of hit points equal to the damage that would be dealt. The target can\
      \ choose to be hit by this attack or fail their saving throw against this effect."
    "name": "Healing Heat"
  - "desc": "The first time a creature other than a fire giant touches the lightbearer\
      \ or hits them with a melee attack on a turn, that creature takes 7 (2d6) fire\
      \ damage."
    "name": "Molten Flesh"
"actions":
  - "desc": "The lightbearer makes two attacks using Slam, Living Blaze, or both.\
      \ They can replace one attack with a use of Flamelash."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 16\
      \ (3d6 + 6) bludgeoning damage plus 7 (2d6) fire damage, and if the target is\
      \ a Huge or smaller creature, the target must choose between being knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ or pushed 10 feet away from the lightbearer."
    "name": "Slam"
  - "desc": "Ranged Spell Attack: +10 to hit, range 180 ft., one target. Hit:\
      \ 16 (3d6 + 6) fire damage, and the lightbearer can ricochet the flame toward\
      \ another target within 5 feet of the first. The lightbearer makes another spell\
      \ attack roll against the second target with disadvantage, dealing the same\
      \ damage on a hit."
    "name": "Living Blaze"
  - "desc": "The lightbearer extends a whiplike flame to strike a creature they can\
      \ see within 30 feet of them. The target must make a DC 18 Dexterity saving\
      \ throw. On a failed save, the target takes 20 (4d6 + 6) fire damage, and if\
      \ the target is Large or smaller, the lightbearer moves the target up to 10\
      \ feet horizontally."
    "name": "Flamelash"
"bonus_actions":
  - "desc": "The lightbearer chooses two willing creatures they can see within 30\
      \ feet of them. Each target takes 14 (4d6) fire damage and teleports, swapping\
      \ places with the other target."
    "name": "Travel by Fire (3/Day)"
"source":
  - "FleeMortals"
```
^statblock