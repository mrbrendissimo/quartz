---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- Harlo Honeygrin
---
# [Harlo Honeygrin](3-Mechanics\CLI\bestiary\npc/harlo-honeygrin-fleemortals.md)
*Source: Flee, Mortals! p. 375*  

```statblock
"name": "Harlo Honeygrin (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling, Ambusher"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "90"
"hit_dice": "20d6 + 20"
"modifier": !!int "5"
"stats":
  - !!int "8"
  - !!int "20"
  - !!int "12"
  - !!int "22"
  - !!int "13"
  - !!int "22"
"speed": "25 ft. (fly 60 ft. in shadow form)"
"saves":
  - "intelligence": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+8"
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+12"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+12"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+9"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks with shadow\
  \ form"
"senses": "passive Perception 11"
"languages": "Common, Dwarvish, Elvish, Halfling, thieves' cant, telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "When Harlo makes an ability check, saving throw, or attack roll, he can\
      \ roll a d6 and add the number rolled to the number rolled on the d20 roll.\
      \ He then takes psychic damage equal to twice the number rolled on the d6.\n\
      \nHarlo can use this die even in his shadow form."
    "name": "Amethyst Die (3/Day)"
  - "desc": "Harlo has advantage on saving throws he makes to avoid or end the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition on himself."
    "name": "Fear Resistant"
  - "desc": "Harlo can communicate telepathically with any Amethyst Knife boss regardless\
      \ of distance, provided they are on the same plane of existence."
    "name": "Mind Link"
  - "desc": "Harlo is immune to any effect that would sense his emotions or read his\
      \ thoughts, as well as to all divination spells."
    "name": "Telepathic Shroud"
"actions":
  - "desc": "Harlo makes two Mind Splinter attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Power Attack: +9 to hit, reach 5 ft. or range 60 ft.,\
      \ one target. Hit: 20 (4d6 + 6) psychic damage, and Harlo is [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ to the target until the start of his next turn."
    "name": "*Mind Splinter (1st-Order Power)"
  - "desc": "Harlo transforms his body into an amorphous shadow, along with everything\
      \ he is wearing or carrying, and gains the following benefits for 10 minutes:\n\
      \n- He has a flying speed of 60 feet.  \n- He has resistance to bludgeoning,\
      \ piercing, and slashing damage from mundane attacks.  \n- He has advantage\
      \ on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth)) checks and can\
      \ attempt to hide without cover.  \n- He can move through a space as narrow\
      \ as 1 inch wide without squeezing.  \n\nWhile in this form, Harlo can't pick\
      \ up or wield objects except for his Amethyst Die."
    "name": "Shadow Form (1/Day; 4th-Order Power; Concentration)"
"bonus_actions":
  - "desc": "Harlo chooses an enemy within 60 feet of him who he can see but who can't\
      \ see him. The target must succeed on a DC 17 Wisdom saving throw or make a\
      \ weapon attack against a creature of Harlo's choice."
    "name": "I'm Over Here"
  - "desc": "Harlo takes the Hide action."
    "name": "Sneaky"
"reactions":
  - "desc": "When Harlo is [blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
      \ or [stunned](/3-Mechanics/CLI/conditions.md#Stunned), he chooses a willing\
      \ Amethyst Knife boss within 60 feet of him who doesn't already have the condition\
      \ or is immune to it. The chosen creature then gains the condition for the duration,\
      \ and Harlo loses the condition. He can use this reaction even while [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Shared Condition"
"source":
  - "FleeMortals"
```
^statblock