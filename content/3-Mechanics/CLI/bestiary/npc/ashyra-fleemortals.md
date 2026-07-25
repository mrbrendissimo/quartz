---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ashyra
---
# [Ashyra](3-Mechanics\CLI\bestiary\npc/ashyra-fleemortals.md)
*Source: Flee, Mortals! p. 266*  

```statblock
"name": "Ashyra (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "225"
"hit_dice": "30d8 + 90"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "15"
  - !!int "19"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "7"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 19"
"languages": "Common, telepathy 60 ft."
"cr": "15"
"traits":
  - "desc": "If Ashyra fails a saving throw, she can choose to succeed instead. When\
      \ she does, she must either end the effect of her Ancient Curse on one enemy\
      \ within 120 feet of her or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of her next turn."
    "name": "Atonement (3/Day)"
  - "desc": "Whenever Ashyra takes piercing or slashing damage, each creature within\
      \ 5 feet of her takes 9 (2d8) poison damage."
    "name": "Mummy Dust"
"actions":
  - "desc": "Ashyra makes two attacks using Desiccating Slam, Soul Fire, or both,\
      \ and she uses Ancient Curse."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 14\
      \ (3d6 + 4) bludgeoning damage plus 10 (3d6) necrotic damage. The target's speed\
      \ is reduced to 0, and they can't regain hit points until the start of Ashyra's\
      \ next turn."
    "name": "Desiccating Slam"
  - "desc": "Ranged Spell Attack: +9 to hit, range 60 ft., one target. Hit: 20\
      \ (3d10 + 4) radiant damage, and if the target is a creature, their hit point\
      \ maximum decreases by a number equal to the damage taken. This reduction lasts\
      \ until the target finishes a long rest or is targeted by a cure ailment power\
      \ of 4th order or higher, a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect. The target dies if this effect reduces\
      \ their hit point maximum to 0."
    "name": "Soul Fire (3rd-Level Spell)"
  - "desc": "Ashyra inflicts weakness on one creature she can see within 120 feet\
      \ of her. The target must succeed on a DC 17 Wisdom saving throw or be cursed.\
      \ While the target is cursed in this way, their attacks deal half damage. The\
      \ curse lasts until Ashyra chooses to end it or until removed by a cure ailment\
      \ power, a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell,\
      \ or a similar supernatural effect."
    "name": "Ancient Curse"
"bonus_actions":
  - "desc": "Ashyra teleports up to 30 feet to an unoccupied space she can see."
    "name": "Misty Step (2nd-Level Spell)"
"reactions":
  - "desc": "When a creature Ashyra can see within 60 feet of her deals damage to\
      \ her, Ashyra brings down the weight of ages on them. The creature must succeed\
      \ on a DC 17 Strength saving throw or be [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the end of their next turn."
    "name": "Weight of Ages"
"legendary_actions":
  - "desc": "Ashyra has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "A storm of stinging dirt whirls around Ashyra in a 15-foot-radius until\
      \ the end of her next turn. For the duration, that area is heavily obscured,\
      \ and when a creature starts their turn in or enters that area for the first\
      \ time on a turn, they must succeed on a DC 17 Constitution saving throw or\
      \ take 22 (4d10) necrotic damage."
    "name": "Action 1: Sands of the Ancients"
  - "desc": "Ashyra bursts into a cloud of dust and makes one Desiccating Slam attack\
      \ against each enemy within 60 feet of her, then she reforms in an unoccupied\
      \ space within 60 feet of her original location."
    "name": "Action 2: Dust to Dust"
  - "desc": "Ashyra commands the land to entomb her foes. Each enemy within 30 feet\
      \ of her must make a DC 17 Strength saving throw. On a failed save, a target\
      \ takes 21 (6d6) bludgeoning damage and is entombed in stone. On a successful\
      \ save, a target takes half as much damage and is not entombed. An entombed\
      \ creature is [restrained](/3-Mechanics/CLI/conditions.md#Restrained), has total\
      \ cover against attacks and other effects outside the stone, and takes 7 (2d6)\
      \ necrotic damage at the end of each of their turns. The creature can be freed\
      \ if the stone is destroyed (AC 17; 30 hit points; immunity to poison and psychic\
      \ damage)."
    "name": "Action 3: Last Rites"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ashyra-fleemortals.png"
```
^statblock