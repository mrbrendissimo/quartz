---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/controller
- ttrpg-cli/monster/type/fiend/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Cackler
---
# [Gnoll Cackler](3-Mechanics\CLI\bestiary\fiend/gnoll-cackler-fleemortals.md)
*Source: Flee, Mortals! p. 119*  

```statblock
"name": "Gnoll Cackler (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Controller"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Abyssal, Gnoll"
"cr": "2"
"actions":
  - "desc": "The cackler makes one Bite attack or one Chill Touch attack and uses\
      \ Moment of Brutality."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
      \ (1d4 + 2) piercing damage plus 2 (d4) necrotic damage."
    "name": "Bite"
  - "desc": "Ranged Spell Attack: +5 to hit, range 120 ft., one creature. Hit:\
      \ 9 (2d8) necrotic damage, and the target can't regain hit points until the\
      \ start of the cackler's next turn."
    "name": "Chill Touch (Cantrip)"
  - "desc": "The cackler targets a creature they can see within 30 feet of them, magically\
      \ flooding them with fury. The target must make a DC 13 Wisdom saving throw,\
      \ which they can choose to fail. A creature who can't be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ succeeds on this saving throw automatically. On a failed save, the target\
      \ takes 7 (2d6) psychic damage, then makes a Bite attack against a creature\
      \ of the cackler's choice within 5 feet of the target. If the target has no\
      \ Bite attack, they make an unarmed strike that deals piercing damage equal\
      \ to d4 + their Strength modifier on a hit."
    "name": "Moment of Brutality"
  - "desc": "The cackler unleashes a spine-chilling laugh. Each enemy within 30 feet\
      \ of them who can hear them must succeed on a DC 13 Wisdom saving throw or be\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the cackler for\
      \ 1 minute (save ends at end of turn)."
    "name": "Fiendish Cackle (Recharge 5-6)"
"reactions":
  - "desc": "When an ally the cackler can see within 30 feet of them is reduced to\
      \ 0 hit points, the cackler moves up to half their speed and makes a Bite attack."
    "name": "Death Frenzy"
  - "desc": "When a creature who the cackler can see within 30 feet of them dies,\
      \ the cackler magically teleports into the space the creature occupied."
    "name": "Fell Teleport"
"source":
  - "FleeMortals"
```
^statblock