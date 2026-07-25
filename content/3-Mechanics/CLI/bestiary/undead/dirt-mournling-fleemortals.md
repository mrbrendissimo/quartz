---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dirt Mournling
---
# [Dirt Mournling](3-Mechanics\CLI\bestiary\undead/dirt-mournling-fleemortals.md)
*Source: Flee, Mortals! p. 263*  

```statblock
"name": "Dirt Mournling (FleeMortals)"
"size": "Huge"
"type": "undead"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "253"
"hit_dice": "22d12 + 110"
"modifier": !!int "3"
"stats":
  - !!int "22"
  - !!int "17"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "40 ft., burrow 40 ft., climb 40 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "11"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "understands the languages of their creator but can't speak"
"cr": "18"
"traits":
  - "desc": "When the mournling dies, the sadness they contain is released into the\
      \ world. Each creature within 30 feet of the mournling who can hear them must\
      \ make a DC 19 Wisdom saving throw, taking 22 (4d10) psychic damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Anguish Unleashed"
  - "desc": "The mournling is immune to any power, spell, or effect that would alter\
      \ their form."
    "name": "Immutable Form"
  - "desc": "When the mournling leaves a space, the ground in that space becomes difficult\
      \ terrain for their enemies for 10 minutes."
    "name": "Puddle of Mud"
"actions":
  - "desc": "The mournling makes three attacks using Slam, Mudslide, or both, and\
      \ they can use Dust Storm, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 28\
      \ (4d10 + 6) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 20). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Slam"
  - "desc": "Ranged Weapon Attack: +12 to hit, range 30/60 ft., one target. Hit:\
      \ 22 (3d10 + 6) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ the target and each Huge or smaller creature of the mournling's choice within\
      \ 5 feet of the target are pulled up to 30 feet toward the mournling."
    "name": "Mudslide"
  - "desc": "The mournling hurls dirt, gravel, and sand. Each creature within 60 feet\
      \ of them must succeed on a DC 19 Constitution saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Dust Storm (1/Day)"
"bonus_actions":
  - "desc": "The mournling teleports to an unoccupied space they can see within 30\
      \ feet of them."
    "name": "Break and Reform"
"reactions":
  - "desc": "When the mournling is hit by a melee weapon attack, they capture the\
      \ weapon that struck them in quickhardening mud, disarming the attacker. A creature\
      \ who can reach the weapon can use an action or bonus action to make a DC 19\
      \ Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check, freeing\
      \ the weapon on a success. The mournling can't use this reaction on attacks\
      \ made with natural weapons."
    "name": "Stuck Fast"
"source":
  - "FleeMortals"
```
^statblock