---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lord Syuul
---
# [Lord Syuul](3-Mechanics\CLI\bestiary\npc/lord-syuul-fleemortals.md)
*Source: Flee, Mortals! p. 287*  

```statblock
"name": "Lord Syuul (FleeMortals)"
"size": "Medium"
"type": "aberration"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "18"
  - !!int "22"
  - !!int "20"
  - !!int "21"
"speed": "30 ft., fly 30 ft."
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "11"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+16"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "bludgeoning"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "15"
"traits":
  - "desc": "If Lord Syuul fails a saving throw while grappling at least one enemy,\
      \ he can choose to release all [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ creatures and succeed on the saving throw instead."
    "name": "Draw In"
"actions":
  - "desc": "Lord Syuul makes two Tentacle or two Psionic Repeater attacks then manifests\
      \ a power or uses Memory Transfer."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 28\
      \ (4d10 + 6) psychic damage, and if the target is Large or smaller, they are\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 19)."
    "name": "Tentacle"
  - "desc": "Ranged Weapon Attack: +11 to hit, range 150/600 ft., one target. Hit:\
      \ 22 (3d10 + 6) force damage."
    "name": "Psionic Repeater"
  - "desc": "Lord Syuul creates a sudden surge of energy in the mind of a creature\
      \ he can see within 120 feet of him. The target must make a DC 19 Constitution\
      \ saving throw, taking 77 (14d10) psychic damage on a failed save, or half as\
      \ much damage on a successful one. If the target has a brain and is reduced\
      \ to 0 hit points, their brain explodes, and if they can't survive without their\
      \ brain, they die."
    "name": "Brain Overload (1/Day; 6th-Order Power)"
  - "desc": "Lord Syuul shoots a 15-foot cone of psionic energy from his eyes. Each\
      \ creature in that area must make a DC 19 Intelligence saving throw, taking\
      \ 35 (10d6) psychic damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Flay (6th-Order Power)"
  - "desc": "Lord Syuul psionically plunders the mind of each creature he is grappling.\
      \ Each target must succeed on a DC 19 Intelligence saving throw or take 44 (8d10)\
      \ psychic damage. If a target fails their saving throw and doesn't escape the\
      \ grapple by the end of their next turn, they must choose one of these effects:\n\
      \n- The target's proficiency bonus drops to 0, they can't form new thoughts\
      \ or speak, and they have disadvantage on all ability checks, attack rolls,\
      \ and saving throws. Only the cure ailment power, a [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or a similar supernatural effect can end this effect. Additionally,\
      \ until Lord Syuul finishes a long rest, he gains a cumulative +5 bonus to damage\
      \ rolls.  \n- The target is [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by Lord Syuul for 1 hour. While the target is [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ Lord Syuul can issue the target telepathic commands (no action required),\
      \ which the target does their best to obey. Each time the target takes damage,\
      \ they can make a DC 19 Wisdom saving throw, ending the effect on a success.\
      \  "
    "name": "Memory Transfer"
  - "desc": "Lord Syuul projects a psionic image over his body, transforming his appearance\
      \ for 1 hour into that of a Medium creature he has seen. When he manifests this\
      \ power, he can also change the appearance of any equipment he carries.\n\n\
      The changes wrought by this power fail to hold up to physical inspection. A\
      \ creature can use an action to inspect Lord Syuul's appearance and make a DC\
      \ 19 Intelligence ([Investigation](/3-Mechanics/CLI/skills.md#Investigation))\
      \ check, noticing the image is a projection on a success."
    "name": "Guise (3rd-Order Power)"
"bonus_actions":
  - "desc": "Lord Syuul and each creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by him teleport up to 30 feet to an unoccupied space he can see."
    "name": "Grappling Jaunt"
"reactions":
  - "desc": "When a creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by\
      \ Lord Syuul makes a saving throw against Memory Transfer, Lord Syuul momentarily\
      \ weakens the creature and the creature has disadvantage on the saving throw."
    "name": "Brain Drain"
"legendary_actions":
  - "desc": "Lord Syuul has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Each enemy Lord Syuul can see within 60 feet of him must make a DC 19\
      \ Wisdom saving throw. On a failed save, a creature can't see creatures other\
      \ than Lord Syuul for 1 minute (save ends at end of turn)."
    "name": "Action 1: Mindblind"
  - "desc": "Lord Syuul becomes [invisible](/3-Mechanics/CLI/conditions.md#Invisible),\
      \ teleports 60 feet to an unoccupied space he can see, and can take the Hide\
      \ action. At the same time, an illusory psionic image of Lord Syuul appears\
      \ in the space he left, gesturing, speaking, and behaving as he chooses (no\
      \ action required). A creature who touches the image for the first time on a\
      \ turn or makes a melee attack against it must succeed on a DC 19 Constitution\
      \ saving throw or take 21 (6d6) psychic damage because things can pass through\
      \ it. Lord Syuul's invisibility ends and his image disappears at the end of\
      \ his next turn."
    "name": "Action 2: Was I Ever Here?"
  - "desc": "Each enemy Lord Syuul can see within 60 feet of him must make a DC 19\
      \ Wisdom saving throw. On a failed save, a target takes 55 (10d10) psychic damage\
      \ and is [dazed](/3-Mechanics/CLI/conditions.md#Dazed) for 1 minute (save ends\
      \ at end of turn). On a successful save, a target takes half as much damage\
      \ and isn't [dazed](/3-Mechanics/CLI/conditions.md#Dazed)."
    "name": "Action 3: Mindshatter"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/lord-syuul-fleemortals.png"
```
^statblock