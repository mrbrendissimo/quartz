---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lord Erasmus Deseo
---
# [Lord Erasmus Deseo](3-Mechanics\CLI\bestiary\humanoid/lord-erasmus-deseo-fleemortals.md)
*Source: Flee, Mortals! p. 363*  

```statblock
"name": "Lord Erasmus Deseo (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Support"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "10"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+4"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "4"
"traits":
  - "desc": "When Erasmus makes an attack, he has advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "At the start of a combat encounter, Erasmus chooses when he acts in the\
      \ initiative order after all other creatures have rolled initiative."
    "name": "Master Tactician"
"actions":
  - "desc": "Erasmus makes two Greatsword attacks. He can replace one attack with\
      \ a use of I'm Right Here."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d6 + 5) slashing damage. If the target is a creature, they have disadvantage\
      \ on attack rolls against creatures other than Erasmus until the end of their\
      \ next turn."
    "name": "Greatsword"
  - "desc": "Erasmus taunts a creature he can see within 5 feet of him who can hear\
      \ him. The creature must succeed on a DC 15 Wisdom saving throw or use their\
      \ reaction, if available, to attack Erasmus. If the creature attacks, an ally\
      \ within 30 feet of Erasmus who isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ can make a weapon attack against the creature (no action required)."
    "name": "I'm Right Here"
  - "desc": "If not in the Cyst, Erasmus teleports to the Cyst. If in the Cyst, he\
      \ teleports to a place he has visited."
    "name": "Iron Ring (2/Day)"
"bonus_actions":
  - "desc": "Erasmus chooses a creature he can see within 60 feet of him and marks\
      \ them until the start of his next turn. The first time one of Erasmus's allies\
      \ deals damage to a marked creature on each turn, the creature takes an extra\
      \ 3 (d6) damage."
    "name": "Mark"
  - "desc": "Erasmus and each ally within 60 feet of him who can hear him moves up\
      \ to 5 feet without provoking opportunity attacks."
    "name": "Reposition"
"source":
  - "FleeMortals"
```
^statblock