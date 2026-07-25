---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vivienn Dirroze
---
# [Vivienn Dirroze](3-Mechanics\CLI\bestiary\npc/vivienn-dirroze-fleemortals.md)
*Source: Flee, Mortals! p. 390*  

```statblock
"name": "Vivienn Dirroze (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Brute"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "152"
"hit_dice": "16d8 + 80"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "11"
  - !!int "20"
  - !!int "11"
  - !!int "12"
  - !!int "24"
"speed": "30 ft."
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+3"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+10"
"damage_resistances": "acid; necrotic; bludgeoning, piercing, slashing during draconic\
  \ rage"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 11"
"languages": "Common, Draconic"
"cr": "7"
"traits":
  - "desc": "When Vivienn makes an attack, she has advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "At the start of her turn, Vivienn can gain advantage on all melee weapon\
      \ attack rolls made during her turn, but attack rolls made against her have\
      \ advantage until the start of her next turn."
    "name": "Reckless"
"actions":
  - "desc": "Vivienn makes three Godslayer Axe attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 14\
      \ (1d12 + 8) slashing damage plus 4 (d8) necrotic damage. If the target is a\
      \ Celestial, they take an extra 18 (4d8) necrotic damage."
    "name": "Godslayer Axe"
"bonus_actions":
  - "desc": "Vivienn roars with the might of dragons, entering a rage that lasts for\
      \ 1 minute or until she is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\
      \ While raging, she gains the following benefits:\n\n- Her size becomes Large.\
      \  \n- She has a +2 bonus to weapon damage rolls.  \n- She has advantage on\
      \ Strength ability checks and saving throws.  \n- She has resistance to bludgeoning,\
      \ piercing, and slashing damage.  "
    "name": "Draconic Rage (3/Day)"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 14\
      \ (1d12 + 8) piercing damage, and the target must succeed on a DC 19 Constitution\
      \ saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of Vivienn for 1 minute (save ends at end of turn)."
    "name": "Ravenous Bite (Draconic Rage Only)"
"source":
  - "FleeMortals"
```
^statblock