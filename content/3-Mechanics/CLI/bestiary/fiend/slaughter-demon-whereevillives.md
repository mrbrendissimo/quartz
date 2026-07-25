---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/brute
- ttrpg-cli/monster/type/fiend/category-3
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Slaughter Demon
---
# [Slaughter Demon](3-Mechanics\CLI\bestiary\fiend/slaughter-demon-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 81, Flee, Mortals! p. 155*  

```statblock
"name": "Slaughter Demon (WhereEvilLives)"
"size": "Huge"
"type": "fiend"
"subtype": "demon, category 3, Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "20"
  - !!int "8"
  - !!int "12"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "3"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "fire"
"condition_immunities": "[flanked](/3-Mechanics/CLI/conditions.md#Flanked)"
"senses": "darkvision 60 ft., soulsight 30 ft., passive Perception 17"
"languages": "Abyssal, Goblin, Infernal"
"cr": "8"
"traits":
  - "desc": "When the demon's soul count is 0, they have advantage on attack rolls,\
      \ disadvantage on saving throws, and their Intelligence score becomes 3 (-4).\
      \ Additionally, the demon must use their movement on each of their turns to\
      \ move as close as possible to the nearest creature they can sense with their\
      \ soulsight, and then if they are able, they must use their action to attack\
      \ and attempt to kill that creature. The demon can't act with any other purpose\
      \ until they add 1 to their soul count."
    "name": "Lethe"
  - "desc": "When the demon reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the demon consumes the creature's\
      \ soul and adds 1 to the demon's soul count. A creature whose soul is consumed\
      \ in this way immediately dies, and they can't be restored to life by any means\
      \ short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell."
    "name": "Soul Devourer"
"actions":
  - "desc": "The demon makes four attacks using Pincer, Sword, Javelin, or a combination\
      \ of them. They can replace one of these attacks with a Tail Spike attack. The\
      \ demon can burn 1 soul to make a fifth attack using Pincer, Sword, or Javelin."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d6 + 6) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 17). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained). The\
      \ demon has six pincers, each of which can grapple a target or wield a weapon."
    "name": "Pincer"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 15\
      \ (2d8 + 6) slashing damage."
    "name": "Sword"
  - "desc": "Melee  or Ranged Weapon Attack: +9 to hit, reach 10 ft. or range 60/240\
      \ ft., one target. Hit: 13 (2d6 + 6) piercing damage."
    "name": "Javelin"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 11\
      \ (1d10 + 6) piercing damage, and the target must succeed on a DC 16 Constitution\
      \ saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) for\
      \ 1 minute (save ends at end of turn)."
    "name": "Tail Spike"
"bonus_actions":
  - "desc": "The demon takes the Disengage action and gains a burrowing speed equal\
      \ to their walking speed until the end of their next turn."
    "name": "Dive Deep (Costs 1 Soul)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/slaughter-demon-whereevillives.png"
```
^statblock