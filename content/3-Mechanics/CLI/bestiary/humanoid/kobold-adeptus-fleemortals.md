---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/kobold
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Adeptus
---
# [Kobold Adeptus](3-Mechanics\CLI\bestiary\humanoid/kobold-adeptus-fleemortals.md)
*Source: Flee, Mortals! p. 171*  

```statblock
"name": "Kobold Adeptus (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Artillery"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "[shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "10"
"hit_dice": "4d6 - 4"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "10"
  - !!int "9"
  - !!int "15"
  - !!int "8"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+1"
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1/8"
"traits":
  - "desc": "The adeptus gains a +1 bonus to AC while within 5 feet of at least one\
      \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the adeptus must be wielding a shield."
    "name": "Shield? Shield!"
"actions":
  - "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one target. Hit: 5\
      \ (2d4) fire damage, and the target must succeed on a DC 12 Constitution saving\
      \ throw or be [deafened](/3-Mechanics/CLI/conditions.md#Deafened) until the\
      \ end of their next turn."
    "name": "Firecracker"
  - "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (d8)\
      \ lightning damage, and the target can't take reactions until the start of their\
      \ next turn. The adeptus has advantage on this attack roll if the target is\
      \ wearing metal armor."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "The adeptus creates three glowing darts of magical force. Each dart hits\
      \ a creature of their choice who they can see within 120 feet of them. A dart\
      \ deals 2 (1d2 + 1) force damage to its target. The darts all strike simultaneously,\
      \ and the adeptus can direct them to hit one creature or several. This action\
      \ is considered to be the [magic missile](/3-Mechanics/CLI/spells/magic-missile-xphb.md)\
      \ spell for the purpose of other spells and effects."
    "name": "Lesser Magic Missile (1/Day; 1st-Level Spell)"
"source":
  - "FleeMortals"
```
^statblock