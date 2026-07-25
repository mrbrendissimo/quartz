---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/category-2
- ttrpg-cli/monster/type/fiend/demon
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ruinant
---
# [Ruinant](3-Mechanics\CLI\bestiary\fiend/ruinant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 163, Flee, Mortals! p. 59*  

```statblock
"name": "Ruinant (WhereEvilLives)"
"size": "Medium"
"type": "fiend"
"subtype": "demon, category 2, Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "14"
  - !!int "18"
  - !!int "16"
"speed": "60 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "darkvision 120 ft., soulsight 30 ft., passive Perception 17"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "When the ruinant's soul count is 0, they have advantage on attack rolls,\
      \ disadvantage on saving throws, and their Intelligence score becomes 3 (-4).\
      \ Additionally, the ruinant must use their movement on each of their turns to\
      \ move as close as possible to the nearest creature they can sense with their\
      \ soulsight, and then if they are able, they must use their action to attack\
      \ and attempt to kill that creature. The ruinant can't act with any other purpose\
      \ until they add 1 to their soul count."
    "name": "Lethe"
  - "desc": "When the ruinant reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the ruinant consumes the creature's\
      \ soul and adds 1 to the ruinant's soul count. A creature whose soul is consumed\
      \ in this way immediately dies, and they can't be restored to life by any means\
      \ short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell."
    "name": "Soul Devourer"
"actions":
  - "desc": "The ruinant makes three Bloodletting Claws attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 7\
      \ (1d6 + 4) piercing damage plus 7 (2d6) necrotic damage, and the target can't\
      \ take reactions this turn."
    "name": "Bloodletting Claws"
  - "desc": "The ruinant chooses up to three creatures they can see within 60 feet\
      \ of them who don't have all their hit points. Each target must make a DC 15\
      \ Constitution saving throw, taking 16 (3d10) necrotic damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "Salt Wounds (Costs 1 Soul)"
"reactions":
  - "desc": "When a creature within 60 feet of the ruinant regains hit points from\
      \ a power, a spell, or a similar supernatural effect, the ruinant corrupts the\
      \ effect. The target regains no hit points, and the target and each of the ruinant's\
      \ enemies within 5 feet of the ruinant must succeed on a DC 15 Constitution\
      \ saving throw or take necrotic damage equal to half the number of hit points\
      \ the effect would have restored."
    "name": "Corrupt Healing (Costs 1 Soul)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/ruinant-fleemortals.png"
```
^statblock