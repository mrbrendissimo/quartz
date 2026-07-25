---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lestheris Soldrei
---
# [Lestheris Soldrei](3-Mechanics\CLI\bestiary\npc/lestheris-soldrei-fleemortals.md)
*Source: Flee, Mortals! p. 352*  

```statblock
"name": "Lestheris Soldrei (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf, Artillery"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "18"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+6"
  - "name": "[Investigation](/3-Mechanics/CLI/skills.md#Investigation)"
    "desc": "+6"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "In addition to any other spells in this stat block, Lestheris can cast\
      \ the following spells, using Intelligence as the spellcasting ability (spell\
      \ save DC 14):\n\nAt will: [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [message](/3-Mechanics/CLI/spells/message-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n3/day each: [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day each: [knock](/3-Mechanics/CLI/spells/knock-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [speak with dead](/3-Mechanics/CLI/spells/speak-with-dead-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time\
      \ |\n|-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action\
      \ |\n| R | 1 reaction |\n| + | Longer than 1 action (see spell description)\
      \ |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "Lestheris has advantage on saving throws to avoid or end the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ condition on herself."
    "name": "Charm Resistant"
  - "desc": "Each other creature within 30 feet of Lestheris has disadvantage on death\
      \ saving throws."
    "name": "Dark Calling"
  - "desc": "Lestheris can see 120 feet into the Ethereal Plane."
    "name": "Tome of the Ethereal"
"actions":
  - "desc": "Lestheris makes two Grave Grasp or two Necrotic Lance attacks."
    "name": "Multiattack"
  - "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (2d6)\
      \ necrotic damage, and the target can't regain hit points until the start of\
      \ Lestheris's next turn."
    "name": "Grave Grasp (Cantrip)"
  - "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit: 9\
      \ (2d8) necrotic damage.\n\nLestheris can destroy a shade under her control\
      \ within 30 feet of her and deal an extra 4 (d8) necrotic damage to the target."
    "name": "Necrotic Lance (1st-Level Spell)"
  - "desc": "Lestheris animates two shades.\n\nThe shades appear in unoccupied spaces\
      \ Lestheris can see within 30 feet of her. The shades act immediately after\
      \ Lestheris on the same initiative count and follow her verbal orders. If Lestheris\
      \ dies, the shades are destroyed."
    "name": "Animate Spirits (2/Day)"
"reactions":
  - "desc": "When a creature Lestheris can see within 60 feet of her targets her with\
      \ an attack, power, or spell while she isn't on the Ethereal Plane, she can\
      \ choose one of the following effects:\n\n- Lestheris enters the Ethereal Plane,\
      \ then returns to the plane and the space she left at the start of her next\
      \ turn.  \n\nIf that space is occupied, she returns to the nearest unoccupied\
      \ space of her choice.\n\n• She teleports up to 60 feet to an unoccupied space\
      \ she can see."
    "name": "Ethereal Step (3/Day)"
"source":
  - "FleeMortals"
```
^statblock