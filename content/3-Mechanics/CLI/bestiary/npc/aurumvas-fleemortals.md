---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/category-6
- ttrpg-cli/monster/type/fiend/demon
- ttrpg-cli/monster/type/fiend/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Aurumvas
---
# [Aurumvas](3-Mechanics\CLI\bestiary\npc/aurumvas-fleemortals.md)
*Source: Flee, Mortals! p. 62*  

```statblock
"name": "Aurumvas (FleeMortals)"
"size": "Huge"
"type": "fiend"
"subtype": "demon, category 6, Leader"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "273"
"hit_dice": "26d12 + 104"
"modifier": !!int "2"
"stats":
  - !!int "25"
  - !!int "15"
  - !!int "18"
  - !!int "22"
  - !!int "20"
  - !!int "21"
"speed": "40 ft., fly 40 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "10"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+10"
"damage_resistances": "necrotic; psychic; bludgeoning, piercing, slashing from mundane\
  \ attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "darkvision 120 ft., soulsight 30 ft., passive Perception 20"
"languages": "all, telepathy 120 ft."
"cr": "14"
"traits":
  - "desc": "When Aurumvas fails a saving throw, he succeeds instead."
    "name": "Abyssal Resistance (Costs 2 Souls)"
  - "desc": "When Aurumvas's soul count is 0, he has advantage on attack rolls, disadvantage\
      \ on saving throws, and his Intelligence score becomes 3 (-4). Additionally,\
      \ Aurumvas must use his movement on each of his turns to move as close as possible\
      \ to the nearest creature he can sense with his soulsight, and then if he is\
      \ able, he must use his action to attack and attempt to kill that creature.\
      \ Aurumvas can't act with any other purpose until he adds 1 to his soul count."
    "name": "Lethe"
  - "desc": "When Aurumvas reduces a creature who isn't a Construct or an Undead to\
      \ 0 hit points or deals damage to a dying creature, the creature must make a\
      \ DC 11 Wisdom saving throw. On a failed save, Aurumvas consumes the creature's\
      \ soul and adds 1 to his soul count. A creature whose soul is consumed in this\
      \ way immediately dies, and they can't be restored to life by any means short\
      \ of a [wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell."
    "name": "Soul Devourer"
  - "desc": "While Aurumvas's soul count is 2 or higher, his weapon attacks are magical,\
      \ and allies within 60 feet of him deal an extra 5 (d10) psychic damage with\
      \ weapon attacks."
    "name": "Soul Weapons"
"actions":
  - "desc": "Aurumvas makes three attacks using Greedy Hands, Covetous Bolt, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one creature. Hit:\
      \ 14 (2d6 + 7) bludgeoning damage plus 10 (3d6) psychic damage. Aurumvas can\
      \ burn 1 soul to gain temporary hit points equal to the psychic damage dealt."
    "name": "Greedy Hands"
  - "desc": "Ranged Spell Attack: +11 to hit, range 120 ft., one target. Hit:\
      \ 22 (5d8) force damage. If the target has spell slots, Aurumvas can burn 2\
      \ souls to force the target to expend their highest-level spell slot available\
      \ with no effect."
    "name": "Covetous Bolt"
"bonus_actions":
  - "desc": "Aurumvas chooses an object he can see within 30 feet of him that is worth\
      \ at least 100 gp. He teleports to an unoccupied space within 5 feet of that\
      \ object."
    "name": "Greed Is Good"
"reactions":
  - "desc": "If a demon with a soul count of 1 or higher who Aurumvas can see dies\
      \ within 60 feet of him, Aurumvas gains 1 soul."
    "name": "Absorb Soul"
"legendary_actions":
  - "desc": "Aurumvas has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Aurumvas warps time with his supernatural greed. Each ally he can see\
      \ within 120 feet of him moves up to their speed. At the end of this round of\
      \ combat, Aurumvas rearranges the initiative order in any way he chooses."
    "name": "Action 1: Time Is Money"
  - "desc": "Aurumvas chooses up to three magic items he can see within 30 feet of\
      \ him that aren't artifacts or of legendary rarity and that don't require attunement.\
      \ He teleports each item to an ally who he can see within 30 feet of him, placing\
      \ it either into their hands or at their feet. If a targeted object is being\
      \ worn or carried by an enemy, the enemy can make a DC 19 Charisma saving throw,\
      \ preventing that object from being teleported on a success."
    "name": "Action 2: That's Ours"
  - "desc": "Aurumvas teleports Tiny explosive treasures from his vault to four different\
      \ points he can see within 120 feet of him. Each creature within 10 feet of\
      \ one or more of these points must make a DC 19 Dexterity saving throw, taking\
      \ 33 (6d10) force damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Action 3: At Any Cost"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/aurumvas-whereevillives.png"
```
^statblock