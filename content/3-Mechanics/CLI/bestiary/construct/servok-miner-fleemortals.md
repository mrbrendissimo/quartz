---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Servok Miner
---
# [Servok Miner](3-Mechanics\CLI\bestiary\construct/servok-miner-fleemortals.md)
*Source: Flee, Mortals! p. 279*  

```statblock
"name": "Servok Miner (FleeMortals)"
"size": "Large"
"type": "construct"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d10 + 80"
"modifier": !!int "-2"
"stats":
  - !!int "22"
  - !!int "6"
  - !!int "20"
  - !!int "3"
  - !!int "8"
  - !!int "1"
"speed": "20 ft., burrow 20 ft., climb 20 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "understands Dwarvish but can't speak"
"cr": "10"
"traits":
  - "desc": "The miner is immune to any power, spell, or effect that would alter their\
      \ form."
    "name": "Immutable Form"
  - "desc": "The miner has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
  - "desc": "The miner can burrow through solid rock at half their burrowing speed\
      \ and leaves a 5-foot-diameter tunnel in their wake."
    "name": "Tunneler"
"actions":
  - "desc": "The miner makes two attacks using Drill Press, Pneumatic Pick, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 15\
      \ (2d8 + 6) piercing damage. If the target is touching the ground, they are\
      \ knocked [prone](/3-Mechanics/CLI/conditions.md#Prone) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by the miner's drill. While [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in this way, the target takes 15 (2d8 + 6) piercing damage at the start of\
      \ each of their turns, and the miner can't make Drill Press attacks. The [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition ends if the miner moves, makes a Drill Press attack, or is destroyed.\
      \ The target or a creature who can reach them can use an action to pull the\
      \ target away from the drill, ending the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition and dealing 15 (2d8 + 6) piercing damage to the target in the process."
    "name": "Drill Press"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 17\
      \ (2d10 + 6) piercing damage. If the target is wearing mundane armor, their\
      \ armor takes a permanent and cumulative -1 penalty to the AC it offers.\n\n\
      Armor reduced to an AC of 10 is destroyed."
    "name": "Pneumatic Pick"
  - "desc": "The miner hurls rocks and dirt in a 30-foot cone. Each creature in that\
      \ area must make a DC 18 Dexterity saving throw. On a failed save, a creature\
      \ takes 44 (8d10) bludgeoning damage and is [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the end of their next turn. On a successful save, a creature takes half\
      \ as much damage and is not [blinded](/3-Mechanics/CLI/conditions.md#Blinded)."
    "name": "Unload Rocks (Recharge 6)"
"bonus_actions":
  - "desc": "The miner strikes the ground and creates a fissure extending from them\
      \ in a 30-foot-long, 5-foot-wide, 30-foot-deep line. Each Medium or smaller\
      \ creature in that area must make a DC 18 Dexterity saving throw. On a failed\
      \ save, a creature falls into the fissure, taking 10 (3d6) bludgeoning damage\
      \ from the fall and landing [prone](/3-Mechanics/CLI/conditions.md#Prone). On\
      \ a successful save, a creature is shunted 5 feet into an unoccupied space and\
      \ does not fall into the fissure. If a creature doesn't have an unoccupied space\
      \ within 5 feet of them, they fall into the fissure."
    "name": "Break Ground (Recharge 6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/construct/token/servok-miner-fleemortals.png"
```
^statblock