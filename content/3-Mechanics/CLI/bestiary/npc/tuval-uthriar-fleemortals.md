---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tuval-Uthriar
---
# [Tuval-Uthriar](3-Mechanics\CLI\bestiary\npc/tuval-uthriar-fleemortals.md)
*Source: Flee, Mortals! p. 371*  

```statblock
"name": "Tuval-Uthriar (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, Soldier"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "[mithral plate](/3-Mechanics/CLI/items/mithral-armor-xdmg.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Elvish, Sylvan"
"cr": "4"
"traits":
  - "desc": "In addition to any other spells in this stat block, Tuval-Uthriar can\
      \ cast the following spells, using Charisma as the spellcasting ability (spell\
      \ save DC 15):\n\nAt will: [light](/3-Mechanics/CLI/spells/light-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [message](/3-Mechanics/CLI/spells/message-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n3/day each: [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [speak with animals](/3-Mechanics/CLI/spells/speak-with-animals-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day each: [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [find traps](/3-Mechanics/CLI/spells/find-traps-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>, [pass without trace](/3-Mechanics/CLI/spells/pass-without-trace-xphb.md)\
      \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time\
      \ |\n|-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action\
      \ |\n| R | 1 reaction |\n| + | Longer than 1 action (see spell description)\
      \ |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "When a creature targets Tuval-Uthriar with an attack, power, or spell,\
      \ the creature must succeed on a DC 15 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by him until the end of his next turn (no action required)."
    "name": "Elf Glamour (1/Day)"
  - "desc": "Tuval-Uthriar has advantage on saving throws against powers, spells,\
      \ and other supernatural effects."
    "name": "Supernatural Resistance"
  - "desc": "Each enemy within 30 feet of Tuval-Uthriar has disadvantage on attacks\
      \ against creatures other than him."
    "name": "Wheel of Ire"
"actions":
  - "desc": "Tuval-Uthriar makes three Longsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (1d8\
      \ + 5) slashing damage, or 10 (1d10 + 5) slashing damage if used with two hands."
    "name": "Longsword"
  - "desc": "A magical bolt of lightning flashes down from the sky to a point Tuval-Uthriar\
      \ can see within 120 feet of him. Each creature within 5 feet of that point\
      \ must make a DC 15 Dexterity saving throw, taking 16 (3d10) lightning damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Call Lightning (3/Day; 3rd-Level Spell)"
  - "desc": "Tuval-Uthriar's gauntlet emits a fiery explosion in a 30-foot cone. The\
      \ explosion can be heard 300 feet away. Each creature in that area must make\
      \ a DC 15 Dexterity saving throw, taking 17 (5d6) fire damage plus 17 (5d6)\
      \ force damage on a failed save, or half as much damage on a successful one.\
      \ Each structure and mundane object in the area that isn't being worn or carried\
      \ takes 35 (10d6) fire damage plus 35 (10d6) force damage."
    "name": "Eye of Sunrise (1/Day)"
"bonus_actions":
  - "desc": "Tuval-Uthriar targets one creature who isn't a Construct or an Undead\
      \ who he can see within 60 feet of him. The target regains 8 (2d4 + 3) hit points."
    "name": "Healing Word (2nd-Level Spell)"
"source":
  - "FleeMortals"
```
^statblock