---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Hunter
---
# [Lizardfolk Hunter](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-hunter-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 107, Flee, Mortals! p. 185*  

```statblock
"name": "Lizardfolk Hunter (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "30 ft., swim 30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+0 plus PB"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2 plus PB"
"senses": "passive Perception 0"
"languages": "Common, Draconic"
"actions":
  - "desc": "Melee Attack Roll: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 2d6 plus PB slashing damage. Beginning at 7th level, the hunter can make this\
      \ attack twice, instead of once, when they take the Attack action on their turn."
    "name": "Signature Attack (Greatsword)"
  - "desc": "As an action, the hunter makes a signature attack against a Large or\
      \ smaller creature. On a hit, the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 10 plus PB). Until the grapple ends, the target takes PB piercing\
      \ damage at the end of each of their turns, and the hunter can't use their Wrenching\
      \ Bite against another target."
    "name": "3rd Level: Wrenching Bite (3/Day)"
  - "desc": "As an action, the hunter makes a signature attack against a Large or\
      \ smaller creature. On a hit, the target must succeed on a DC 10 plus PB Dexterity\
      \ saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone). While\
      \ the hunter is within 5 feet of this [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ target, the target can't stand up unless they use an action to make a DC 10\
      \ plus PB Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check.\
      \ On a success, the target can stand up."
    "name": "5th Level: Thrashing Tail (3/Day)"
  - "desc": "As a bonus action, the hunter drones lullingly. Each creature within\
      \ 5 feet of the hunter who can hear them must succeed on a DC 10 plus PB Constitution\
      \ saving throw or fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ for 1 minute. An [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)\
      \ target wakes up if they take damage, the hunter becomes [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ the hunter moves more than 5 feet away from the target, or another creature\
      \ uses an action to rouse the target."
    "name": "7th Level: Hypnotic Sleep (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lizardfolk-hunter-fleemortals.png"
```
^statblock