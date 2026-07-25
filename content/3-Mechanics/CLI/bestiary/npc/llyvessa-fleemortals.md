---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Llyvessa
---
# [Llyvessa](3-Mechanics\CLI\bestiary\npc/llyvessa-fleemortals.md)
*Source: Flee, Mortals! p. 376*  

```statblock
"name": "Llyvessa (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, Artillery"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[studded leather armor](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "6"
"stats":
  - !!int "10"
  - !!int "22"
  - !!int "13"
  - !!int "15"
  - !!int "17"
  - !!int "12"
"speed": "35 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+9"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Elvish, telepathy 120 ft."
"cr": "5"
"traits":
  - "desc": "Attacking at long range with a ranged weapon doesn't impose disadvantage\
      \ on Llyvessa's attack rolls."
    "name": "Deadly Sharpshooter"
  - "desc": "When a creature targets Llyvessa with an attack, power, or spell, the\
      \ creature must succeed on a DC 14 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by her until the end of her next turn (no action required)."
    "name": "Elf Glamour (1/Day)"
  - "desc": "Llyvessa can communicate telepathically with any Amethyst Knife boss\
      \ regardless of distance, provided they are on the same plane of existence."
    "name": "Mind Link"
"actions":
  - "desc": "Llyvessa makes two Scimitar or Longbow attacks. Alternatively, she makes\
      \ one Longbow attack and uses Psychic Shot, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d6\
      \ + 6) slashing damage."
    "name": "Scimitar"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. Hit:\
      \ 15 (2d8 + 6) piercing damage."
    "name": "Longbow"
  - "desc": "Llyvessa makes a Longbow attack that ignores cover, and which can pass\
      \ through mundane solid objects up to 5 feet thick that aren't being worn or\
      \ carried."
    "name": "Psychic Shot (Recharge 5-6)"
"bonus_actions":
  - "desc": "Llyvessa or one willing creature within 5 feet of her teleports to an\
      \ unoccupied space Llyvessa can see within 30 feet of her."
    "name": "Jaunt (1/Day; 3rd-Order Power)"
"reactions":
  - "desc": "When a creature Llyvessa can see within 60 feet of her makes a ranged\
      \ weapon attack, she gives the creature advantage or disadvantage on the attack\
      \ roll (her choice)."
    "name": "*Control Projectiles (3/Day; 2nd-Order Power)"
  - "desc": "When Llyvessa is [blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
      \ or [stunned](/3-Mechanics/CLI/conditions.md#Stunned), she chooses a willing\
      \ Amethyst Knife boss within 60 feet of her who doesn't already have the condition\
      \ or is immune to it. The chosen creature then gains the condition for the duration,\
      \ and Llyvessa loses the condition. She can use this reaction even while [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Shared Condition"
"source":
  - "FleeMortals"
```
^statblock