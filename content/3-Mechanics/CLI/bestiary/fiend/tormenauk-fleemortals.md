---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/brute
- ttrpg-cli/monster/type/fiend/category-3
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tormenauk
---
# [Tormenauk](3-Mechanics\CLI\bestiary\fiend/tormenauk-fleemortals.md)
*Source: Flee, Mortals! p. 60*  

```statblock
"name": "Tormenauk (FleeMortals)"
"size": "Large"
"type": "fiend"
"subtype": "demon, category 3, Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "13d10 + 65"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "5"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "darkvision 120 ft., soulsight 30 ft., passive Perception 15"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "8"
"traits":
  - "desc": "When the tormenauk's soul count is 0, they have advantage on attack rolls,\
      \ disadvantage on saving throws, and their Intelligence score becomes 3 (-4).\
      \ Additionally, the tormenauk must use their movement on each of their turns\
      \ to move as close as possible to the nearest creature they can sense with their\
      \ soulsight, and then if they are able, they must use their action to attack\
      \ and attempt to kill that creature. The tormenauk can't act with any other\
      \ purpose until they add 1 to their soul count."
    "name": "Lethe"
  - "desc": "When the tormenauk reduces a creature who isn't a Construct or an Undead\
      \ to 0 hit points or deals damage to a dying creature, the creature must make\
      \ a DC 11 Wisdom saving throw. On a failed save, the tormenauk consumes the\
      \ creature's soul and adds 1 to the tormenauk's soul count. A creature whose\
      \ soul is consumed in this way immediately dies, and they can't be restored\
      \ to life by any means short of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell."
    "name": "Soul Devourer"
"actions":
  - "desc": "The tormenauk makes two Slam attacks and one Many Maws attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
      \ (2d8 + 5) bludgeoning damage. If the target is Large or smaller, they are\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 15), and they\
      \ are [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until the grapple\
      \ ends. The tormenauk can grapple up to two targets at a time."
    "name": "Slam"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the tormenauk. Hit: 21 (3d10 + 5) piercing damage."
    "name": "Many Maws"
  - "desc": "The tormenauk screeches, broadcasting a consumed soul's lifelong pain.\
      \ Each creature within 30 feet of the tormenauk who can hear them must make\
      \ a DC 15 Wisdom saving throw, taking 35 (10d6) psychic damage on a failed save,\
      \ or half as much damage on a successful one. Creatures who knew the owner of\
      \ the burned soul have disadvantage on the saving throw."
    "name": "Agony Wail (Costs 1 Soul)"
"reactions":
  - "desc": "When the tormenauk takes damage, they choose a creature they can see\
      \ within 30 feet of them to share the pain. The target must make a DC 15 Wisdom\
      \ saving throw, taking psychic damage equal to the triggering damage taken by\
      \ the tormenauk on a failed save, or half as much damage on a successful one."
    "name": "Share Agony (Costs 1 Soul)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/tormenauk-whereevillives.png"
```
^statblock