---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/brute
- ttrpg-cli/monster/type/fiend/category-5
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Chimeron
---
# [Chimeron](3-Mechanics\CLI\bestiary\fiend/chimeron-fleemortals.md)
*Source: Flee, Mortals! p. 58*  

```statblock
"name": "Chimeron (FleeMortals)"
"size": "Huge"
"type": "fiend"
"subtype": "demon, category 5, Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "1"
"stats":
  - !!int "24"
  - !!int "12"
  - !!int "20"
  - !!int "16"
  - !!int "14"
  - !!int "12"
"speed": "30 ft., fly 30 ft."
"saves":
  - "strength": !!int "11"
  - "dexterity": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "cold, fire, thunder"
"senses": "darkvision 120 ft., soulsight 30 ft., passive Perception 16"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "While the chimeron's soul count is 0, they have advantage on attack rolls,\
      \ disadvantage on saving throws, and their Intelligence score becomes 3 (-4).\
      \ Additionally, the chimeron must use their movement on each of their turns\
      \ to move as close as possible to the nearest creature they can sense with their\
      \ soulsight, and then if they are able, they must use their action to attack\
      \ and attempt to kill that creature. The chimeron can't act with any other purpose\
      \ until they add 1 to their soul count."
    "name": "Lethe"
  - "desc": "When the chimeron reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the chimeron consumes the creature's\
      \ soul and adds 1 to the chimeron's soul count. A creature whose soul is consumed\
      \ in this way immediately dies, and they can't be restored to life by any means\
      \ short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell."
    "name": "Soul Devourer"
  - "desc": "While the chimeron's soul count is is 2 or higher, they have advantage\
      \ on saving throws against powers, spells, and other supernatural effects."
    "name": "Soul Resistance"
"actions":
  - "desc": "The chimeron makes up to three attacks using Powerful Bite, Scorching\
      \ Bite, Booming Bite, or Chilling Bite. They can't use any attack more than\
      \ once."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 25\
      \ (4d8 + 7) piercing damage."
    "name": "Powerful Bite"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 11\
      \ (1d8 + 7) piercing damage plus 9 (2d8) fire damage, and the target is set\
      \ on fire until the target or a creature who can reach them uses an action to\
      \ extinguish the flames. A creature who is on fire at the start of their turn\
      \ takes 7 (2d6) fire damage. If a creature who is already on fire is set on\
      \ fire again on a subsequent turn, the damage isn't cumulative."
    "name": "Scorching Bite"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 11\
      \ (1d8 + 7) piercing damage plus 9 (2d8) thunder damage, and the target is knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Booming Bite (Costs 1 Soul)"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 11\
      \ (1d8 + 7) piercing damage plus 9 (2d8) cold damage, the target's speed is\
      \ halved until the end of their next turn, and they can only make one attack\
      \ during their next turn."
    "name": "Chilling Bite (Costs 1 Soul)"
"reactions":
  - "desc": "When the chimeron takes damage, they reduce the damage taken by 16 (3d10)."
    "name": "Pain Absorption (Costs 1 Soul)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/chimeron-fleemortals.png"
```
^statblock