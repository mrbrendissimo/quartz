---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/goblin
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goblin Assassin
---
# [Goblin Assassin](3-Mechanics\CLI\bestiary\humanoid/goblin-assassin-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 22, Flee, Mortals! p. 126*  

```statblock
"name": "Goblin Assassin (WhereEvilLives)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Ambusher"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1/2"
"traits":
  - "desc": "When the assassin has advantage on their attack roll against a creature\
      \ who isn't a Construct or an Undead, their attacks deal an extra 3 (d6) damage\
      \ and inflict a bleeding wound on the target that lasts until the bleeding creature\
      \ regains at least 1 hit point. A bleeding creature loses 2 hit points for each\
      \ bleeding wound they have at the start of their turn. Any creature who can\
      \ reach the target can use an action to stanch all the target's wounds, ending\
      \ the effect."
    "name": "Backstab"
  - "desc": "The assassin doesn't provoke opportunity attacks when they move out of\
      \ an enemy's reach."
    "name": "Crafty"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) slashing damage."
    "name": "Scimitar"
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
  - "desc": "A 10-foot-radius sphere of magical darkness emanates from a point the\
      \ assassin can see for 1 minute. The darkness spreads around corners. Except\
      \ for the assassin, a creature with darkvision can't see through this darkness,\
      \ and mundane light can't illuminate it. At the start of their turn, the assassin\
      \ can move the darkness up to 30 feet to a point they can see (no action required).\
      \ If the assassin takes damage, the effect ends."
    "name": "Summon Shadows (1/Day)"
"bonus_actions":
  - "desc": "The assassin takes the Hide action."
    "name": "Sneak"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock