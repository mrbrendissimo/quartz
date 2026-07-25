---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/artillery
- ttrpg-cli/monster/type/fiend/category-4
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wobalas
---
# [Wobalas](3-Mechanics\CLI\bestiary\fiend/wobalas-fleemortals.md)
*Source: Flee, Mortals! p. 61*  

```statblock
"name": "Wobalas (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "demon, category 4, Artillery"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "6"
"stats":
  - !!int "14"
  - !!int "22"
  - !!int "14"
  - !!int "16"
  - !!int "18"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
"senses": "darkvision 120 ft., soulsight 30 ft., passive Perception 18"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "When the wobalas's soul count is 0, they have advantage on attack rolls,\
      \ disadvantage on saving throws, and their Intelligence score becomes 3 (-4).\
      \ Additionally, the wobalas must use their movement on each of their turns to\
      \ move as close as possible to the nearest creature they can sense with their\
      \ soulsight, and then if they are able, they must use their action to attack\
      \ and attempt to kill that creature. The wobalas can't act with any other purpose\
      \ until they add 1 to their soul count."
    "name": "Lethe"
  - "desc": "When the wobalas reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the wobalas consumes the creature's\
      \ soul and adds 1 to the wobalas's soul count. A creature whose soul is consumed\
      \ in this way immediately dies, and they can't be restored to life by any means\
      \ short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell."
    "name": "Soul Devourer"
"actions":
  - "desc": "The wobalas makes three Despair Bolt attacks."
    "name": "Multiattack"
  - "desc": "Ranged Weapon Attack: +10 to hit, range 150/600 ft., one creature.\
      \ Hit: 16 (3d6 + 6) piercing damage plus 10 (3d6) psychic damage. The wobalas\
      \ can burn 1 soul to make the target [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of them for 1 minute. If the target is immune to being [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
      \ the wobalas regains the burned soul."
    "name": "Despair Bolt"
  - "desc": "Melee Spell Attack: +8 to hit, reach 5 ft., one creature. Hit: 22\
      \ (4d10) psychic damage, and the target is teleported up to 30 feet to an unoccupied\
      \ space the wobalas can see."
    "name": "Banishing Touch"
"bonus_actions":
  - "desc": "The wobalas chooses a creature they can see within 60 feet of them. The\
      \ target must succeed on a DC 16 Charisma saving throw or use their reaction,\
      \ if available, to move their speed away from the wobalas by the most direct\
      \ route possible, with no regard for their own safety. Creatures who can't be\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) succeed on this saving\
      \ throw automatically."
    "name": "Flee, Mortal (Costs 1 Soul)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/wobalas-whereevillives.png"
```
^statblock