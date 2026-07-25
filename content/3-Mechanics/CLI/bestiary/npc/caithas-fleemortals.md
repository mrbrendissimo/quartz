---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- Caithas
---
# [Caithas](3-Mechanics\CLI\bestiary\npc/caithas-fleemortals.md)
*Source: Flee, Mortals! p. 389*  

```statblock
"name": "Caithas (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling, Artillery"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "8"
"stats":
  - !!int "10"
  - !!int "26"
  - !!int "14"
  - !!int "14"
  - !!int "26"
  - !!int "12"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "11"
  - "constitution": !!int "5"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+11"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+11"
"damage_resistances": "acid, fire, necrotic"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic, Infernal"
"cr": "7"
"traits":
  - "desc": "When Caithas is in forest terrain and is targeted by a ranged attack\
      \ by an attacker he can see, the attack has disadvantage."
    "name": "Forest Defense"
"actions":
  - "desc": "Caithas makes three Scimitar or three Scaled Longbow attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 15\
      \ (2d6 + 8) slashing damage."
    "name": "Scimitar"
  - "desc": "Ranged Weapon Attack: +11 to hit, range 150/600 ft., one target. Hit:\
      \ 12 (1d8 + 8) piercing damage plus 7 (2d6) necrotic damage. If the target is\
      \ a creature who hasn't attacked Caithas since the end of his last turn, he\
      \ has advantage on the attack roll."
    "name": "Scaled Longbow"
  - "desc": "Caithas calls on his connection with Qazyldrath, and the dragon manifests\
      \ in Caithas's space and exhales dark energy in a 30-foot line that is 5 feet\
      \ wide. Each creature in that line must make a DC 19 Dexterity saving throw,\
      \ taking 18 (4d8) acid damage plus 18 (4d8) necrotic damage on a failed save,\
      \ or half as much damage on a successful one. Additionally, that area is filled\
      \ with magical darkness for 1 minute. A creature with darkvision can't see through\
      \ this darkness, and supernatural light can't illuminate it. The manifestation\
      \ of Qazyldrath then disappears."
    "name": "Manifestation (Recharge 5-6)"
"bonus_actions":
  - "desc": "Caithas chooses a creature he can see within 60 feet of him, magically\
      \ marking them for 24 hours. While Caithas and the marked creature are on the\
      \ same plane of existence, he always knows the distance and direction to them.\
      \ Additionally, a marked creature can't hide from him, and if the marked creature\
      \ becomes [invisible](/3-Mechanics/CLI/conditions.md#Invisible), they gain no\
      \ benefit from that condition against Caithas."
    "name": "Gaze of the Decay (1/Day)"
"source":
  - "FleeMortals"
```
^statblock