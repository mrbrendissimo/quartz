---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Xaantikorijek
---
# [Xaantikorijek](3-Mechanics\CLI\bestiary\npc/xaantikorijek-fleemortals.md)
*Source: Flee, Mortals! p. 83*  

```statblock
"name": "Xaantikorijek (FleeMortals)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "Solo"
"alignment": "Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "518"
"hit_dice": "28d20 + 224"
"modifier": !!int "0"
"stats":
  - !!int "28"
  - !!int "10"
  - !!int "27"
  - !!int "24"
  - !!int "16"
  - !!int "20"
"speed": "40 ft., burrow 40 ft., fly 80 ft."
"saves":
  - "constitution": !!int "15"
  - "wisdom": !!int "10"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+21"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+21"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+21"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+21"
"damage_immunities": "lightning, thunder"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 20"
"languages": "all"
"cr": "23"
"traits":
  - "desc": "When Xaantikorijek fails a saving throw, he can succeed instead. When\
      \ he does, his sight, blindsight, and truesight are reduced to a range of 30\
      \ feet until the start of his next turn."
    "name": "Static Shield (3/Day)"
  - "desc": "Lightning and thunder damage dealt by Xaantikorijek ignore damage resistance."
    "name": "Storm of the Gods"
"actions":
  - "desc": "Xaantikorijek makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 20\
      \ (2d10 + 9) piercing damage plus 5 (d10) lightning damage, and Xaantikorijek\
      \ can move the target up to 20 feet in any direction."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 16\
      \ (2d6 + 9) slashing damage plus 7 (2d6) thunder damage, and the target is knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Claw"
  - "desc": "Xaantikorijek exhales lightning in a line that is 120 feet long and 30\
      \ feet wide. Each creature in that area must make a DC 23 Dexterity saving throw.\
      \ On a failed save, a creature takes 66 (12d10) lightning damage and has disadvantage\
      \ on saving throws until the end of Xaantikorijek's next turn. On a successful\
      \ save, a creature takes half as much damage and suffers no other effect."
    "name": "Fulminating Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Xaantikorijek makes one Bite attack. On a hit, Xaantikorijek's teeth\
      \ spark with energy, dealing an extra 11 (2d10) lightning damage to the target\
      \ and to one other enemy within 60 feet of the target."
    "name": "Lightning Discharge"
"reactions":
  - "desc": "When a creature Xaantikorijek can see within 60 feet of him uses an action\
      \ or bonus action to cast a spell, Xaantikorijek speaks an arcane word, forcing\
      \ the creature to make a DC 23 saving throw using their spellcasting ability.\
      \ On a failed save, the target takes 16 (3d10) thunder damage and is unable\
      \ to cast spells until the end of their turn, but the spell slot is not expended\
      \ and the creature's action is not lost."
    "name": "Voice of Negation"
"legendary_actions":
  - "desc": "Xaantikorijek has three villain actions. He can take each action once\
      \ during an encounter after an enemy's turn. He can take these actions in any\
      \ order but can use only one per round."
    "name": ""
  - "desc": "Xaantikorijek speaks an ancient word of authority into the mind of each\
      \ creature of his choice within 60 feet of him. Each target must succeed on\
      \ a DC 20 Wisdom saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ A creature who falls [prone](/3-Mechanics/CLI/conditions.md#Prone) in this\
      \ way takes 22 (4d10) thunder damage if they stand up before the end of Xaantikorijek's\
      \ next turn."
    "name": "Action 1: Voice of Reverence"
  - "desc": "Xaantikorijek sheds his physical form to become a being of lightning\
      \ until the end of his next turn. While in this form, Xaantikorijek gains the\
      \ following benefits:\n\n- He is resistant to all damage.  \n- He can move through\
      \ a space as narrow as 1 inch wide without squeezing.  \n- His movement doesn't\
      \ provoke opportunity attacks.  \n- He can move through any creature's space,\
      \ and when he moves into a creature's space for the first time on a turn, that\
      \ creature takes 16 (3d10) lightning damage.  "
    "name": "Action 2: Fulguration"
  - "desc": "Xaantikorijek recites an ancient lament that reverberates in nearby souls.\
      \ Each enemy within 60 feet of Xaantikorijek who can hear him must make a DC\
      \ 20 Wisdom saving throw. On a failed save, a creature takes 44 (8d10) psychic\
      \ damage, falls [prone](/3-Mechanics/CLI/conditions.md#Prone), and is unable\
      \ to stand up for 1 minute as they weep uncontrollably (save ends at end of\
      \ turn). On a successful save, a creature takes half as much damage and suffers\
      \ no other effect."
    "name": "Action 3: Voice of the Ages"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/xaantikorijek-fleemortals.png"
```
^statblock