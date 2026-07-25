---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/lizardfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Bloodeye Slime Servant
---
# [Lizardfolk Bloodeye Slime Servant](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-bloodeye-slime-servant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 135*  

If a creature spends 1 continuous minute under the effect of the slime from an olothec's Devolving Tentacle attack, that effect ends and their flesh devolves into a translucent primordial state. The creature loses their memories and sense of self, becoming a slime servant NPC who is loyal to the olothec.

```statblock
"name": "Lizardfolk Bloodeye Slime Servant (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Controller"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "16"
  - !!int "11"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Common, Draconic"
"cr": "2"
"traits":
  - "desc": "The bloodeye can breathe air and water."
    "name": "Amphibious"
  - "desc": "Ithu'rath can sense anything the bloodeye senses, and Ithu'rath can speak\
      \ through their body."
    "name": "Servant Senses"
"actions":
  - "desc": "The bloodeye makes one Bite or one Bola attack and uses Bloodeye Bolt\
      \ or Mesmeric Lure, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit:\
      \ 7 (1d8 + 3) bludgeoning damage, and the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by the bola. A creature can use their action to make a DC 10 Strength check,\
      \ freeing themself or another creature within their reach from the bola on a\
      \ success. Dealing 5 slashing damage to the bola (AC 10) destroys it and frees\
      \ a creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by it without\
      \ harming them."
    "name": "Bola"
  - "desc": "The bloodeye shoots blood from their eyes at one creature they can see\
      \ within 30 feet of them. The target must succeed on a DC 13 Constitution saving\
      \ throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded) for 1 minute\
      \ (save ends at end of turn)."
    "name": "Bloodeye Bolt (3/Day)"
  - "desc": "The bloodeye hypnotically stares at one creature they can see within\
      \ 30 feet of them. The target must succeed on a DC 13 Wisdom saving throw or\
      \ all creatures other than the bloodeye are [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ to them until the end of the bloodeye's next turn."
    "name": "Mesmeric Lure (3/Day)"
"reactions":
  - "desc": "If the bloodeye fails a Strength or Dexterity saving throw, they lose\
      \ their tail and succeed instead. They regrow their tail when they finish a\
      \ long rest."
    "name": "Reptilian Escape (1/Day)"
"source":
  - "WhereEvilLives"
```
^statblock