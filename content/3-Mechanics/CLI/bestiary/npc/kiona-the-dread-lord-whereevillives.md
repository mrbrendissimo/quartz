---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/incorporeal
- ttrpg-cli/monster/type/undead/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kiona the Dread Lord
---
# [Kiona the Dread Lord](3-Mechanics\CLI\bestiary\npc/kiona-the-dread-lord-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 89, Flee, Mortals! p. 249*  

```statblock
"name": "Kiona the Dread Lord (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "incorporeal, Leader"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "4"
"stats":
  - !!int "9"
  - !!int "18"
  - !!int "18"
  - !!int "20"
  - !!int "14"
  - !!int "13"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from mundane attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "blindsight 60 ft., passive Perception 16"
"languages": "Common, Draconic, Orc"
"cr": "9"
"traits":
  - "desc": "Kiona can move through other creatures and objects. Kiona takes 5 (d10)\
      \ force damage if she ends her turn inside an object. A creature takes 9 (2d8)\
      \ necrotic damage the first time Kiona passes through them on a turn."
    "name": "Corrupting Phasing"
  - "desc": "Each incorporeal Undead within 120 feet of Kiona ignores difficult terrain."
    "name": "Incorporeal Empowerment"
  - "desc": "When Kiona fails a saving throw, she can lose 15 hit points and choose\
      \ to succeed instead."
    "name": "Spiritual Sacrifice (3/Day)"
"actions":
  - "desc": "Kiona makes two Energy Siphon attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 120\
      \ ft., one creature. Hit: 15 (3d6 + 5) necrotic damage, and the target can't\
      \ regain hit points until the start of Kiona's next turn. Kiona gains temporary\
      \ hit points equal to half the damage dealt by this attack."
    "name": "Energy Siphon"
  - "desc": "Kiona conjures three shadows, two specters, or one wraith under her control.\
      \ Each summoned creature appears in an unoccupied space within 30 feet of Kiona\
      \ and acts immediately after her turn on the same initiative count."
    "name": "Rise from Death (1/Day)"
"bonus_actions":
  - "desc": "Kiona chooses one other incorporeal Undead within 120 feet of her who\
      \ can see her. That Undead can move up to their speed."
    "name": "Path of Pain"
"reactions":
  - "desc": "When a creature within 5 feet of Kiona hits her with an attack, she breathes\
      \ a toxin at the creature. The creature must succeed on a DC 17 Constitution\
      \ saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until\
      \ the end of their next turn."
    "name": "Death's Breath"
"legendary_actions":
  - "desc": "Kiona has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "A 20-foot-radius sphere of spectral arms emerges from a point Kiona can\
      \ see within 120 feet of her. Each enemy in that area must succeed on a DC 17\
      \ Dexterity saving throw or be [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the end of Kiona's next turn."
    "name": "Action 1: Restrain Them!"
  - "desc": "Kiona and each ally within 60 feet of her can move up to their speed\
      \ without provoking opportunity attacks."
    "name": "Action 2: Ruinous March"
  - "desc": "Kiona and each ally within 60 feet of her can make a melee attack (no\
      \ action required). A creature hit by one of these attacks gains a level of\
      \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)."
    "name": "Action 3: Vitality Drain"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/kiona-the-dread-lord-whereevillives.webp"
```
^statblock