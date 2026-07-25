---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wight
---
# [Wight](3-Mechanics\CLI\bestiary\undead/wight-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 223, Flee, Mortals! p. 255*  

```statblock
"name": "Wight (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "Soldier"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages they knew in life"
"cr": "3"
"actions":
  - "desc": "The wight makes one Longsword attack and one Vitality Theft attack, or\
      \ they make two Heavy Crossbow attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) slashing damage."
    "name": "Longsword"
  - "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
      \ 6 (1d10 + 1) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one creature. Hit: 9\
      \ (2d8) necrotic damage, and the wight regains a number of hit points equal\
      \ to half the damage dealt. Until the start of the wight's next turn, the target\
      \ has disadvantage on attack rolls made against creatures other than the wight."
    "name": "Vitality Theft"
"reactions":
  - "desc": "When an ally the wight can see within 5 feet of them is hit by an attack,\
      \ the wight forces the attacker to reroll the attack and to instead target the\
      \ wight or a willing ally within 5 feet of the original target."
    "name": "Decaying Guard"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock