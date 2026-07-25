---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Voiceless Talker Artillerist
---
# [Voiceless Talker Artillerist](3-Mechanics\CLI\bestiary\aberration/voiceless-talker-artillerist-fleemortals.md)
*Source: Flee, Mortals! p. 283*  

```statblock
"name": "Voiceless Talker Artillerist (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Artillery"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "16"
  - !!int "21"
  - !!int "17"
  - !!int "16"
"speed": "30 ft., fly 30 ft."
"saves":
  - "constitution": !!int "7"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "bludgeoning"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "When the artillerist hits a target with their Psionic Rifle attack, the\
      \ artillerist can attempt to teleport the target (no action required). The target\
      \ must succeed on a DC 17 Wisdom saving throw or be teleported to an unoccupied\
      \ space the artillerist can see within 60 feet of the artillerist."
    "name": "Phasing Rifle (1/Turn)"
"actions":
  - "desc": "The artillerist makes two Psionic Rifle attacks, or they manifest a power\
      \ and make one Phasing Tentacles attack."
    "name": "Multiattack"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. Hit:\
      \ 21 (3d10 + 5) force damage."
    "name": "Psionic Rifle"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 21\
      \ (3d10 + 5) psychic damage, and if the target is Large or smaller, the artillerist\
      \ can choose one of the following effects: the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 17) or teleported up to 15 feet to an unoccupied space the artillerist\
      \ can see."
    "name": "Phasing Tentacles"
  - "desc": "The artillerist psionically plunders the mind of a creature they can\
      \ see within 30 feet of them. The target must make a DC 17 Intelligence saving\
      \ throw. On a failed save, the target takes 33 (6d10) psychic damage, and until\
      \ they finish a long rest or die, their proficiency bonus is lowered by 1 and\
      \ the artillerist gains a cumulative +2 bonus to damage rolls. On a successful\
      \ save, a target takes half as much damage and doesn't have their proficiency\
      \ bonus reduced.\n\nA creature whose proficiency bonus drops to 0 can't form\
      \ new thoughts or speak, and they have disadvantage on ability checks, attack\
      \ rolls, and saving throws."
    "name": "Memory Thief (5th-Order Power)"
  - "desc": "The artillerist projects a psionic image over their body, transforming\
      \ their appearance for 1 hour into that of a Medium creature they have seen.\
      \ When they manifest this power, they can also change the appearance of any\
      \ equipment they carry for the duration.\n\nThe changes wrought by this power\
      \ fail to hold up to physical inspection. A creature can use an action to inspect\
      \ the artillerist's appearance and make a DC 17 Intelligence ([Investigation](/3-Mechanics/CLI/skills.md#Investigation))\
      \ check, noticing the image is a projection on a success."
    "name": "Guise (3rd-Order Power)"
"bonus_actions":
  - "desc": "The artillerist cloaks themself from the sight of a creature the artillerist\
      \ can see within 60 feet of them. The creature must succeed on a DC 17 Wisdom\
      \ saving throw or the artillerist becomes [invisible](/3-Mechanics/CLI/conditions.md#Invisible)\
      \ to the creature for 1 minute (save ends at end of turn). This effect ends\
      \ early if the artillerist attacks the creature, deals damage to them, or creates\
      \ an effect that forces them to make a saving throw."
    "name": "Vanish for One (3/Day; 3rd-Order Power; Concentration)"
"source":
  - "FleeMortals"
```
^statblock