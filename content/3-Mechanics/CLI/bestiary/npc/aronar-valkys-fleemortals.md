---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Aronar Valkys
---
# [Aronar Valkys](3-Mechanics\CLI\bestiary\npc/aronar-valkys-fleemortals.md)
*Source: Flee, Mortals! p. 388*  

```statblock
"name": "Aronar Valkys (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf, Support"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "1"
"stats":
  - !!int "26"
  - !!int "12"
  - !!int "14"
  - !!int "14"
  - !!int "26"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "5"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "acid, necrotic"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic, Elvish"
"cr": "8"
"traits":
  - "desc": "In addition to any other spells in this stat block, Aronar can cast the\
      \ following spells, using Wisdom as the spellcasting ability (spell save DC\
      \ 19):\n\nAt will: [augury](/3-Mechanics/CLI/spells/augury-xphb.md) <sup>[+](#^superscript-casting-time)</sup>,\
      \ [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy-xphb.md) <sup>[A](#^superscript-casting-time)</sup>\n\
      \n1/day each: [hallow](/3-Mechanics/CLI/spells/hallow-xphb.md) <sup>[+](#^superscript-casting-time)</sup>,\
      \ [raise dead](/3-Mechanics/CLI/spells/raise-dead-xphb.md) <sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "Aronar has advantage on saving throws he makes to avoid or end the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ condition on himself."
    "name": "Charm Resistant"
  - "desc": "Whenever Aronar is affected by an effect (such as the [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md)\
      \ spell) that allows him to make a saving throw at the end of his turn, he can\
      \ also repeat that saving throw at the start of his turn. Additionally, whenever\
      \ Aronar succeeds on a saving throw against an effect, he ends that effect on\
      \ himself and any ally within 30 feet of him under the same effect."
    "name": "Delusions of Grandeur"
  - "desc": "When Aronar is within 30 feet of Athmia and casts a spell that restores\
      \ hit points to another creature, Athmia regains the same number of hit points."
    "name": "Sun Eater's Grace (3/Day)"
"actions":
  - "desc": "Aronar makes three Divine Mace attacks, or he makes one Divine Mace attack\
      \ and one God Complex attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 11\
      \ (1d6 + 8) bludgeoning damage plus 7 (2d6) necrotic damage, and the target\
      \ must succeed on a DC 19 Constitution saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the start of their next turn."
    "name": "Divine Mace"
  - "desc": "Ranged Spell Attack: +11 to hit, range 120 ft., one target. Hit:\
      \ 28 (8d6) necrotic damage, and the next attack roll made against this target\
      \ before the end of Aronar's next turn has advantage."
    "name": "God Complex (3/Day; 3rd-Level Spell)"
  - "desc": "Aronar touches a creature and the target regains 21 (3d8 + 8) hit points."
    "name": "Cure Wounds (3/Day; 3rd-Level Spell)"
"bonus_actions":
  - "desc": "A creature of Aronar's choice within 60 feet of him regains 15 (3d4 +\
      \ 8) hit points."
    "name": "Vainglory (3/Day; 3rd-Level Spell)"
"reactions":
  - "desc": "When a creature Aronar can see within 30 feet of him is hit with an attack,\
      \ he can halve the attack's damage dealt to them."
    "name": "Sun Eater's Soul (3/Day)"
"source":
  - "FleeMortals"
```
^statblock