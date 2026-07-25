---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Athmia Valkys
---
# [Athmia Valkys](3-Mechanics\CLI\bestiary\npc/athmia-valkys-fleemortals.md)
*Source: Flee, Mortals! p. 389*  

```statblock
"name": "Athmia Valkys (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf, Skirmisher"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "8"
"stats":
  - !!int "10"
  - !!int "26"
  - !!int "14"
  - !!int "26"
  - !!int "12"
  - !!int "13"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "11"
  - "intelligence": !!int "11"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+14"
"damage_resistances": "acid, necrotic"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 17"
"languages": "Common, Draconic, Elvish"
"cr": "8"
"traits":
  - "desc": "Athmia has advantage on saving throws she makes to avoid or end the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ condition on herself."
    "name": "Charm Resistant"
  - "desc": "If Athmia is subjected to an effect that allows her to make a Dexterity\
      \ saving throw to take only half damage, she instead takes no damage if she\
      \ succeeds on the saving throw, and only half damage if she fails."
    "name": "Evasion"
  - "desc": "When Athmia hits a creature with her Soul Blade attack, she can assault\
      \ their mind. The target must succeed on a DC 19 Intelligence saving throw or\
      \ expend one spell slot of the highest level available with no effect. A creature\
      \ who fails this saving throw but can't expend a spell slot must instead spend\
      \ 3 of their Hit Dice with no effect, or if they can't, take an extra 10 (3d6)\
      \ psychic damage."
    "name": "Mental Assault (1/Turn)"
"actions":
  - "desc": "Athmia makes two Soul Blade attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +11 to hit, reach 5 ft. or range 30/60\
      \ ft., one target. Hit: 25 (5d6 + 8) psychic damage, and the target must succeed\
      \ on a DC 19 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of Athmia until the end of her next turn."
    "name": "Soul Blade"
  - "desc": "Athmia clouds the minds of her foes.\n\nEach enemy within 60 feet of\
      \ her must succeed on a DC 19 Wisdom saving throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the start of her next turn. Athmia gains 5 temporary hit points for\
      \ each creature who fails this save."
    "name": "Psychic Frenzy (1/Day)"
"bonus_actions":
  - "desc": "Athmia takes the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "While within 30 feet of Aronar, Athmia swaps places with him if he is\
      \ willing."
    "name": "Sun Eater's Gift (3/Day)"
"reactions":
  - "desc": "When a creature Athmia can see within 60 feet of her makes a spell attack\
      \ against her or casts a spell that requires her to make a saving throw, she\
      \ can pierce their mind, and the next attack she makes against that creature\
      \ is automatically a critical hit."
    "name": "Sun Eater's Mind (3/Day)"
"source":
  - "FleeMortals"
```
^statblock