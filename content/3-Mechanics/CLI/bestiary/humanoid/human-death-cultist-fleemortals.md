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
- Human Death Cultist
---
# [Human Death Cultist](3-Mechanics\CLI\bestiary\humanoid/human-death-cultist-fleemortals.md)
*Source: Flee, Mortals! p. 161*  

```statblock
"name": "Human Death Cultist (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Support"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain mail](/3-Mechanics/CLI/items/chain-mail-xphb.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "18"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "3"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": "Common plus any one language"
"cr": "4"
"traits":
  - "desc": "When the cultist makes an attack, they have advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
      \ + 3) slashing damage plus 7 (2d6) necrotic damage, and the cultist regains\
      \ hit points equal to half the necrotic damage dealt."
    "name": "Scythe"
  - "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 14\
      \ (4d6) necrotic damage, and the target's weapon attacks deal half damage until\
      \ the start of the cultist's next turn."
    "name": "Death Bolt"
  - "desc": "The cultist empowers up to 10 non-minion allies within 30 feet of them.\
      \ For 1 minute or until the cultist dies, each creature's weapons burn with\
      \ black fire and deal an extra 2 (d4) necrotic damage on a hit."
    "name": "Blackfire Blessing (1/Day)"
"bonus_actions":
  - "desc": "The cultist chooses up to three creatures within 30 feet of them who\
      \ died within the last minute. These creatures return to life with 1 hit point,\
      \ but they can't regain hit points, and they die after 1 minute."
    "name": "Rise, My Minions! (1/Day)"
"reactions":
  - "desc": "When a creature the cultist can see within 30 feet of them fails a death\
      \ saving throw or dies, the cultist siphons their faltering life energy. The\
      \ cultist chooses a creature within 30 feet of the cultist who isn't [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious),\
      \ and that creature regains 14 (4d6) hit points."
    "name": "Life from Death"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/human-death-cultist-whereevillives.png"
```
^statblock