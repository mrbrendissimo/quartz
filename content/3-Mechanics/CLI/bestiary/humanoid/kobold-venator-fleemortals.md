---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/kobold
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Venator
---
# [Kobold Venator](3-Mechanics\CLI\bestiary\humanoid/kobold-venator-fleemortals.md)
*Source: Flee, Mortals! p. 177*  

```statblock
"name": "Kobold Venator (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Ambusher"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "14"
"hit_dice": "4d6"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "13"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Draconic"
"cr": "1/4"
"traits":
  - "desc": "The venator begins combat disguised as an inexperienced warrior. They\
      \ have advantage on their first weapon attack roll against a creature who hasn't\
      \ seen them make an attack."
    "name": "Not What I Seem"
  - "desc": "The venator gains a +1 bonus to AC while within 5 feet of at least one\
      \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ or [prone](/3-Mechanics/CLI/conditions.md#Prone). To benefit from this trait,\
      \ the venator must be wielding a shield."
    "name": "Shield? Shield!"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
      \ + 2) slashing damage."
    "name": "Dolabra"
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 5/15\
      \ ft., one Large or smaller creature. Hit: The target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until they are freed. A creature can use their action to make a DC 10 Strength\
      \ check, freeing themself or another creature within their reach on a success.\
      \ Dealing 5 slashing damage to the net (AC 10) also frees the creature without\
      \ harming them and destroys the net. The venator carries one net."
    "name": "Net"
"bonus_actions":
  - "desc": "The venator takes the Hide action. They have advantage on their Dexterity\
      \ ([Stealth](/3-Mechanics/CLI/skills.md#Stealth)) check if they are within 5\
      \ feet of two or more allied kobolds."
    "name": "Lost in the Crowd"
  - "desc": "The venator chooses a creature within 5 feet of them who is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by a net and lights that net on fire. While [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by the net, the target takes 3 (d6) fire damage at the start of each of their\
      \ turns. Each time the net deals damage, roll any die. On an odd result, the\
      \ net burns away and is destroyed, freeing the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ creature. A creature who attempts to free the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ creature from the net (as described in the venator's Net attack) automatically\
      \ puts out the fire as part of that action, regardless of whether that check\
      \ succeeds."
    "name": "Then We Light the Net on Fire!"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-venator-fleemortals.png"
```
^statblock