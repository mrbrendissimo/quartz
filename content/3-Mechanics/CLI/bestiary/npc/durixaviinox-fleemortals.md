---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Durixaviinox
---
# [Durixaviinox](3-Mechanics\CLI\bestiary\npc/durixaviinox-fleemortals.md)
*Source: Flee, Mortals! p. 77*  

```statblock
"name": "Durixaviinox (FleeMortals)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "370"
"hit_dice": "20d20 + 160"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "26"
  - !!int "18"
  - !!int "14"
  - !!int "18"
"speed": "40 ft., burrow 40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "constitution": !!int "14"
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+10"
"damage_immunities": "cold, force"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "20"
"traits":
  - "desc": "When Durixaviinox fails a saving throw, he can succeed instead. When\
      \ he does, his speed is halved and he can't take the Disengage action until\
      \ the end of his next turn."
    "name": "Frosted Resistance (3/Day)"
  - "desc": "Cold damage dealt by Durixaviinox ignores damage resistance."
    "name": "Hoarfrost"
  - "desc": "Durixaviinox can move across and climb icy surfaces without needing to\
      \ make an ability check. Additionally, difficult terrain composed of ice or\
      \ snow doesn't cost him extra movement."
    "name": "Ice Walk"
"actions":
  - "desc": "Durixaviinox makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 19\
      \ (2d10 + 8) piercing damage plus 9 (2d8) cold damage, and the target can't\
      \ take reactions until the end of their next turn."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 15\
      \ (2d6 + 8) slashing damage, and Durixaviinox can move the target up to 15 feet\
      \ horizontally."
    "name": "Claw"
  - "desc": "Durixaviinox exhales a freezing blast in a 90-foot cone. Each creature\
      \ in that area must make a DC 22 Constitution saving throw. On a failed save,\
      \ a creature takes 42 (12d6) cold damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the end of their next turn. On a successful save, a creature takes half\
      \ as much damage and isn't [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Numbing Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Durixaviinox encases a creature he can see within 60 feet of him in ice.\
      \ The target must make a DC 18 Strength saving throw. On a failed save, a creature\
      \ takes 22 (4d10) cold damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ On a successful save, a target takes half as much damage and isn't [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ A creature can use an action to break themself or another creature they can\
      \ reach out of the ice, ending the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition."
    "name": "Icy Grip"
"reactions":
  - "desc": "When a creature within 5 feet of Durixaviinox hits him with an attack,\
      \ Durixaviinox releases a burst of cold energy. Each creature within 5 feet\
      \ of him must succeed on a DC 18 Constitution saving throw or take 10 (3d6)\
      \ cold damage."
    "name": "Withering Frost"
"legendary_actions":
  - "desc": "Durixaviinox has three villain actions. He can take each action once\
      \ during an encounter after an enemy's turn. He can take these actions in any\
      \ order but can use only one per round."
    "name": ""
  - "desc": "Durixaviinox beats his wings, and frigid winds and hail swirl around\
      \ him. Each creature within 120 feet of him must make a DC 18 Strength saving\
      \ throw. On a failed save, a creature takes 21 (6d6) bludgeoning damage, is\
      \ pushed 60 feet directly away from Durixaviinox, and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, a creature takes half as much damage and isn't pushed\
      \ or knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Action 1: Raging Blizzard"
  - "desc": "Durixaviinox calls the faithful soul of a spectral guard to fight at\
      \ his side. The guard uses the frost giant wind sprinter stat block, but they\
      \ are an Undead instead of a Giant. The guard acts immediately after Durixaviinox\
      \ and follows his verbal commands. While the guard is within 60 feet of Durixaviinox,\
      \ Durixaviinox gains resistance to all damage. If Durixaviinox dies, the guard\
      \ is destroyed."
    "name": "Action 2: Royal Defense"
  - "desc": "Durixaviinox releases a pulse of frigid energy followed by a shock wave\
      \ of force in a 120-foot-radius sphere centered on him. Each enemy in that area\
      \ must make a DC 18 Constitution saving throw, taking 45 (10d8) cold damage\
      \ on a failed save, or half as much damage on a successful one. Immediately\
      \ after, each enemy in that area must make a DC 18 Strength saving throw, taking\
      \ 45 (10d8) force damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Action 3: Frost Cataclysm"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/durixaviinox-whereevillives.png"
```
^statblock