---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/illuskan-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Othovir
---
# [Othovir](3-Mechanics\CLI\bestiary\npc/othovir-skt.md)
*Source: Storm King's Thunder p. 255*  

Othovir is a gifted harness-maker who doesn't talk about his family or where he came from. He cares about his business, his clients, and his good name.

Ideal:"Find what you do well, and do it to the best of your ability."

Bond:"I won't allow my name to be tarnished."

Flaw:"I get angry when others pry into my private life."

```statblock
"name": "Othovir (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Lawful Neutral"
"ac": !!int "10"
"ac_class": "13 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "0"
"stats":
  - !!int "11"
  - !!int "10"
  - !!int "13"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": "Common, Elvish"
"traits":
  - "desc": "Othovir is a gifted harness-maker who doesn't talk about his family or\
      \ where he came from. He cares about his business, his clients, and his good\
      \ name.\n\nIdeal: \"Find what you do well, and do it to the best of your ability.\"\
      \n\nBond: \"I won't allow my name to be tarnished.\"\n\nFlaw: \"I get angry\
      \ when others pry into my private life.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (d8)\
      \ piercing damage."
    "name": "Rapier"
  - "desc": "Othovir casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 13; +5 to hit with spell attacks):\n\nAt will:\
      \ [fire bolt](/3-Mechanics/CLI/spells/fire-bolt-xphb.md) (d10 fire damage),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n1/day\
      \ each: [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md),\
      \ [witch bolt](/3-Mechanics/CLI/spells/witch-bolt-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Othovir adds 2 to its AC against one melee attack that would hit him.\
      \ To do so, Othovir must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/othovir-skt.webp"
```
^statblock