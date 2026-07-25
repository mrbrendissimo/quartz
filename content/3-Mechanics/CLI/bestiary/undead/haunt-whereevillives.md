---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Haunt
---
# [Haunt](3-Mechanics\CLI\bestiary\undead/haunt-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 309*  

```statblock
"name": "Haunt (WhereEvilLives)"
"size": "Huge"
"type": "undead"
"subtype": "Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "153"
"hit_dice": "18d12 + 36"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "8"
  - !!int "16"
  - !!int "18"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from mundane attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), flanked, [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "telepathy 60 ft."
"cr": "9"
"traits":
  - "desc": "The haunt can occupy another creature's space and vice versa. In addition,\
      \ the haunt can move through creatures and objects as if they were difficult\
      \ terrain.\n\nThe haunt takes 5 (d10) force damage if they end their turn inside\
      \ an object."
    "name": "Incorporeal Cloud"
  - "desc": "The haunt is [invisible](/3-Mechanics/CLI/conditions.md#Invisible)."
    "name": "Invisibility"
"actions":
  - "desc": "The haunt makes two Spectral Wrath attacks."
    "name": "Multiattack"
  - "desc": "Melee Spell Attack: +8 to hit, reach 0 ft., one target in the haunt's\
      \ space. Hit: 17 (2d12 + 4) force damage."
    "name": "Spectral Wrath"
  - "desc": "The haunt unleashes a wave of psychic pain. Each enemy within 20 feet\
      \ of the haunt must make a DC 16 Wisdom saving throw, taking 33 (6d10) psychic\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Wave of Despair (Recharge 5-6)"
"bonus_actions":
  - "desc": "The haunt can magically manipulate a Large or smaller object within 30\
      \ feet of them that isn't being worn or carried by another creature. The haunt\
      \ can exert fine control on objects under their control, such as playing piano\
      \ keys, slamming doors, opening windows, or writing with a quill.\n\nAs part\
      \ of this bonus action, the haunt can hurl the object up to 30 feet in any direction\
      \ or use it as a ranged weapon to attack one creature within 30 feet of the\
      \ object. The object has a +8 bonus to hit and deals 15 (2d10 + 4) bludgeoning\
      \ damage on a hit. The GM might rule that a specific object deals piercing or\
      \ slashing damage based on its form."
    "name": "Possess Object"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/undead/token/haunt-fleemortals.png"
```
^statblock