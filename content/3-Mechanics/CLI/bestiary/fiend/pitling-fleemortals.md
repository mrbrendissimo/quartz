---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/category-1
- ttrpg-cli/monster/type/fiend/demon
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Pitling
---
# [Pitling](3-Mechanics\CLI\bestiary\fiend/pitling-fleemortals.md)
*Source: Flee, Mortals! p. 58*  

```statblock
"name": "Pitling (FleeMortals)"
"size": "Tiny"
"type": "fiend"
"subtype": "demon, category 1, Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "11"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "3"
  - !!int "6"
  - !!int "6"
"speed": "30 ft., fly 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., soulsight 10 ft., passive Perception 8"
"languages": "Abyssal"
"cr": "4"
"traits":
  - "desc": "If an enemy starts their turn within 10 feet of three or more pitlings,\
      \ the enemy is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the\
      \ start of their next turn."
    "name": "Horrid Stench"
  - "desc": "If the pitling takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the pitling takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When the pitling reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the pitling consumes the creature's\
      \ soul, and the pitling becomes a Category 2 demon of the GM's choice with 1\
      \ soul. A creature whose soul is consumed in this way immediately dies, and\
      \ they can't be restored to life by any means short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell. If the creature was reduced to 0 hit points by a group attack, the\
      \ GM picks one pitling who joined the attack to consume the soul."
    "name": "Soul Feast"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 15/30\
      \ ft., one target. Hit: 4 poison damage."
    "name": "Spit (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/pitling-whereevillives.png"
```
^statblock