---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mirran
---
# [Mirran](3-Mechanics\CLI\bestiary\npc/mirran-skt.md)
*Source: Storm King's Thunder p. 207*  

```statblock
"name": "Mirran (SKT)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "230"
"hit_dice": "20d12 + 100"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "18"
"speed": "50 ft., swim 50 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "10"
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+14"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+9"
"damage_resistances": "cold"
"damage_immunities": "lightning, thunder"
"senses": "passive Perception 19"
"languages": "Common, Giant"
"cr": "13"
"traits":
  - "desc": "Mirran's innate spellcasting ability is Charisma (spell save DC 17).\
      \ It can innately cast the following spells, requiring no material components:\n\
      \nAt will: [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [feather fall](/3-Mechanics/CLI/spells/feather-fall-xphb.md), [levitate](/3-Mechanics/CLI/spells/levitate-xphb.md),\
      \ [light](/3-Mechanics/CLI/spells/light-xphb.md)\n\n3/day each: [control\
      \ weather](/3-Mechanics/CLI/spells/control-weather-xphb.md), [water breathing](/3-Mechanics/CLI/spells/water-breathing-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Mirran can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Mirran makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 30\
      \ (6d6 + 9) slashing damage."
    "name": "Greatsword"
  - "desc": "Ranged Weapon Attack: +14 to hit, range 60/240 ft., one target. Hit:\
      \ 35 (4d12 + 9) bludgeoning damage."
    "name": "Rock"
  - "desc": "Mirran hurls a magical lightning bolt at a point it can see within 500\
      \ feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity\
      \ saving throw, taking 54 (12d8) lightning damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Lightning Strike (Recharge 5-6)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/mirran-skt.webp"
```
^statblock