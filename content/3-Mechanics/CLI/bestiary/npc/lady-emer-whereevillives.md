---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lady Emer
---
# [Lady Emer](3-Mechanics\CLI\bestiary\npc/lady-emer-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 106, Flee, Mortals! p. 190*  

```statblock
"name": "Lady Emer (WhereEvilLives)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"modifier": !!int "7"
"stats":
  - !!int "18"
  - !!int "24"
  - !!int "20"
  - !!int "16"
  - !!int "17"
  - !!int "18"
"speed": "40 ft."
"saves":
  - "strength": !!int "8"
  - "dexterity": !!int "11"
  - "constitution": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+11"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+7"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common, Elvish"
"cr": "11"
"traits":
  - "desc": "When Emer fails a saving throw, she can choose to succeed instead by\
      \ ending the effects of her Stone Gaze on a creature of her choice within 300\
      \ feet of her."
    "name": "Stone Sacrifice (3/Day)"
"actions":
  - "desc": "Emer uses Pinning Shot or makes three attacks using Snake Bite, Longbow,\
      \ or both. She also uses Stone Gaze or Envenomed Stone, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one creature. Hit:\
      \ 17 (5d6) poison damage, and the target must succeed on a DC 17 Constitution\
      \ saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until\
      \ the end of Emer's next turn. While [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ in this way, the target can't take reactions."
    "name": "Snake Bite"
  - "desc": "Ranged Weapon Attack: +11 to hit, range 150/600 ft., one target. Hit:\
      \ 11 (1d8 + 7) piercing damage plus 14 (4d6) poison damage."
    "name": "Longbow"
  - "desc": "Emer makes three Longbow attacks against a creature touching the ground\
      \ within 150 feet of her. If at least two of those attacks hit, the target is\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by arrows pinning\
      \ their limbs to the ground. A creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ in this way or another creature who can reach them can use an action to pull\
      \ out the arrows and end the condition."
    "name": "Pinning Shot"
  - "desc": "Emer fires beams of energy from her eyes at up to three creatures she\
      \ can see within 60 feet of her. Each target must succeed on a DC 17 Constitution\
      \ saving throw or begin turning to stone (save ends at end of turn). While turning\
      \ to stone, a creature's speed is reduced by 10 feet and they have disadvantage\
      \ on Dexterity checks and saving throws. If a creature who is turning to stone\
      \ is targeted by this action again and fails their save, their speed is reduced\
      \ by another 10 feet and they are [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the effect ends.\n\nIf a creature who is turning to stone and [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ in this way is targeted by this action again and fails their save, they are\
      \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified) and can no longer make\
      \ saving throws to end the effects of Stone Gaze. The petrification lasts until\
      \ the creature is restored by Emer's Stone Sacrifice trait, a cure ailment power\
      \ of 4th order or higher, a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect."
    "name": "Stone Gaze"
  - "desc": "Emer utters an ancient hex. Each creature within 60 feet of her who is\
      \ being turned to stone by her Stone Gaze must make a DC 17 Constitution saving\
      \ throw, taking 44 (8d10) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Envenomed Stone (Recharge 5-6)"
"bonus_actions":
  - "desc": "The glowing eyes of Emer's snakes gaze at one creature Emer can see within\
      \ 60 feet of her. If the target can see Emer, they must succeed on a DC 17 Wisdom\
      \ saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed) until\
      \ the start of the target's next turn. A target [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ in this way must immediately use their reaction, if available, to move up\
      \ to their speed in a direction of Emer's choice."
    "name": "Mesmerizing Eyes"
"reactions":
  - "desc": "When a creature Emer can see within 5 feet of her hits her with a melee\
      \ attack, Emer spits venom at their eyes. The target must succeed on a DC 17\
      \ Dexterity saving throw or take 7 (2d6) acid damage and be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the start of their next turn."
    "name": "Blinding Mucus"
"legendary_actions":
  - "desc": "Emer has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Emer uses Stone Gaze against each enemy she can see within 60 feet of\
      \ her."
    "name": "Action 1: I See You!"
  - "desc": "Emer grows wings from her back, gaining a flying speed of 40 feet, then\
      \ she moves up to her speed without provoking opportunity attacks. After 1 minute,\
      \ the wings crumble to dust and her flying speed is lost."
    "name": "Action 2: Medusa's Evolution"
  - "desc": "Emer mentally manipulates the stone in each creature who is being turned\
      \ to stone by her Stone Gaze. Emer and each of those creatures move up to their\
      \ speed then make a weapon attack against a creature of Emer's choice (no action\
      \ required)."
    "name": "Action 3: Stone Puppets"
"lair_actions":
  - "desc": "When fighting inside her lair, Lady Emer can take lair actions. On initiative\
      \ count 20 (losing initiative ties), she can take one lair action to cause one\
      \ of the following effects; she can't use the same lair action two rounds in\
      \ a row:"
    "name": ""
  - "desc": "- Shadowstep. Emer teleports up to 30 feet to an unoccupied space\
      \ she can see.  \n- Stony Wail. The statues in Emer's lair scream in pain.\
      \ Each enemy within 60 feet of Emer who can hear the statues must succeed on\
      \ a DC 15 Wisdom saving throw or be frightened of Emer until the end of initiative\
      \ count 20 on the next round.  \n- Venom Shower. Black venom rains down\
      \ in a 10-footradius, 40-foot-high cylinder centered on a point Emer can see\
      \ within 90 feet of her. Each creature in that area must succeed on a DC 15\
      \ Constitution saving throw or be poisoned until the end of initiative count\
      \ 20 on the next round.  "
    "name": ""
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/lady-emer-whereevillives.webp"
```
^statblock