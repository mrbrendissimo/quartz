---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/category-2
- ttrpg-cli/monster/type/fiend/demon
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tusker Demon
---
# [Tusker Demon](3-Mechanics\CLI\bestiary\fiend/tusker-demon-fleemortals.md)
*Source: Flee, Mortals! p. 122*  

```statblock
"name": "Tusker Demon (FleeMortals)"
"size": "Huge"
"type": "fiend"
"subtype": "demon, category 2, Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-2"
"stats":
  - !!int "22"
  - !!int "6"
  - !!int "20"
  - !!int "5"
  - !!int "10"
  - !!int "8"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "2"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), soulsight 30 ft., passive\
  \ Perception 10"
"languages": "understands Abyssal but can't speak"
"cr": "7"
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
  - "desc": "The demon can move through the spaces of Large or smaller creatures as\
      \ if they were difficult terrain. When the demon enters a creature's space for\
      \ the first time on the demon's turn, the demon can make a Stomp attack against\
      \ that creature (no action required). Additionally, the demon can end their\
      \ turn in the space of a [prone](/3-Mechanics/CLI/conditions.md#Prone) creature\
      \ who is Medium or smaller, and that creature can't stand up while in the demon's\
      \ space."
    "name": "Trample"
"actions":
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 19\
      \ (3d8 + 6) piercing damage. The demon can burn 1 soul to push the target up\
      \ to 40 feet directly away from the demon."
    "name": "Gore"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d6 + 6) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ they must succeed on a DC 17 Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Stomp"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 16\
      \ (3d6 + 6) slashing damage, and if the target is a creature, they must succeed\
      \ on a DC 17 Strength saving throw or be pulled up to 10 feet toward the demon."
    "name": "Tongue"
"reactions":
  - "desc": "When an enemy within 40 feet of the demon deals damage to the demon,\
      \ the demon can move up to their speed straight toward them. If the demon ends\
      \ this movement within 10 feet of the enemy, the demon can make a Gore attack\
      \ against them."
    "name": "Vengeful Charge (Costs 1 Soul)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/tusker-demon-fleemortals.png"
```
^statblock