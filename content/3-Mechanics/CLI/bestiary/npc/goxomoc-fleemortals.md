---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/30
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/solo
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goxomoc
---
# [Goxomoc](3-Mechanics\CLI\bestiary\npc/goxomoc-fleemortals.md)
*Source: Flee, Mortals! p. 236*  

```statblock
"name": "Goxomoc (FleeMortals)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan, Solo"
"alignment": "Neutral"
"ac": !!int "23"
"ac_class": "natural armor"
"hp": !!int "574"
"hit_dice": "28d20 + 280"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "30"
  - !!int "22"
  - !!int "26"
  - !!int "16"
"speed": "50 ft., climb 50 ft., swim 50 ft."
"saves":
  - "dexterity": !!int "9"
  - "intelligence": !!int "15"
  - "wisdom": !!int "17"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+19"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+17"
"damage_immunities": "fire; lightning; poison; thunder; bludgeoning, piercing, slashing\
  \ from mundane attacks"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "truesight 300 ft., passive Perception 27"
"languages": "understands all languages but can't speak, telepathy 150 ft."
"cr": "30"
"traits":
  - "desc": "Goxomoc can breathe air and water."
    "name": "Amphibious"
  - "desc": "Enemies within 60 feet of Goxomoc can't fly, and when Goxomoc moves within\
      \ 60 feet of a flying enemy, the enemy falls."
    "name": "Earthbinder"
  - "desc": "If Goxomoc is reduced to 0 hit points, he sheds his flesh form and becomes\
      \ [Xogomoc](/3-Mechanics/CLI/bestiary/npc/xogomoc-fleemortals.md). Any conditions\
      \ or other supernatural effects that were affecting Goxomoc continue affecting\
      \ Xogomoc."
    "name": "Lightning Lord"
  - "desc": "If Goxomoc fails a saving throw, he can choose to succeed instead, and\
      \ he can't use Energy Eyes or Shockwave until the end of his next turn."
    "name": "Psionic Resistance (3/Day)"
  - "desc": "Goxomoc's weapon attacks are psionic."
    "name": "Psionic Weapons"
  - "desc": "Goxomoc deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Goxomoc makes one Bite attack, two Claw attacks, and one Stomp attack,\
      \ and he uses Energy Eyes."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +19 to hit, reach 10 ft., one target. Hit: 36\
      \ (4d12 + 10) piercing damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 20). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and Goxomoc can't bite another target. If this damage reduces a creature to\
      \ 0 hit points, they die and Goxomoc consumes their remains."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +19 to hit, reach 15 ft., one target. Hit: 21\
      \ (2d10 + 10) slashing damage, and Goxomoc moves the target up to 10 feet horizontally."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +19 to hit, reach 15 ft., one target who isn't\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by Goxomoc. Hit: 23\
      \ (2d12 + 10) bludgeoning damage, and if the target is Huge or smaller, they\
      \ are knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Stomp"
  - "desc": "Goxomoc beams energy from his eyes at a creature he can see within 300\
      \ feet of him. The target must make a DC 25 Dexterity saving throw, taking 22\
      \ (4d10) fire or lightning damage (Goxomoc's choice) on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Energy Eyes (3rd-Order Power)"
  - "desc": "Goxomoc breathes lightning in a 90-foot cone. Each creature in that area\
      \ must make a DC 27 Dexterity saving throw. On a failed save, a creature takes\
      \ 71 (11d12) fire or lightning damage (Goxomoc's choice) and is teleported to\
      \ an unoccupied space of Goxomoc's choice within that area. On a successful\
      \ save, a creature takes half as much damage and isn't teleported."
    "name": "Catastrophic Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "A psionic shock wave emanates from Goxomoc. Each creature of his choice\
      \ within 15 feet of him must succeed on a DC 25 Strength saving throw or take\
      \ 22 (4d10) force damage and be pushed up to 20 feet directly away from him."
    "name": "Shockwave (2nd-Order Power)"
"reactions":
  - "desc": "When Goxomoc takes damage, he teleports along with any creatures he is\
      \ grappling in a burst of lava to an unoccupied space he can see within 30 feet\
      \ of him. Each creature within 10 feet of the space he left must make a DC 27\
      \ Dexterity saving throw, taking 22 (4d10) fire damage on a failed save, or\
      \ half as much damage on a successful one."
    "name": "Volcanic Punishment"
"legendary_actions":
  - "desc": "Goxomoc has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Goxomoc stomps the ground, unleashing a wave of debilitating psionic\
      \ energy. Mundane objects within 90 feet of Goxomoc that aren't being worn or\
      \ carried take 55 (10d10) force damage. Creatures within 90 feet of Goxomoc\
      \ are knocked [prone](/3-Mechanics/CLI/conditions.md#Prone) and must succeed\
      \ on a DC 27 Dexterity saving throw or be [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and embedded in the ground. A creature can use an action to make a DC 20 Strength\
      \ ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) or Dexterity ([Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics))\
      \ check, freeing themself or another creature within their reach on a success."
    "name": "Action 1: Rumble"
  - "desc": "Goxomoc disappears in a crack of thunder, along with any creatures he\
      \ is grappling, and reappears in an unoccupied space he can see within 120 feet\
      \ of him. Each creature within 30 feet of either the space he left or his new\
      \ space must make a DC 27 Constitution saving throw, taking 22 (4d10) thunder\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Action 2: Thunder"
  - "desc": "Goxomoc unleashes a psionic scream of anguish in the mind of enemies\
      \ within 120 feet of him. Each target must make a DC 25 Wisdom saving throw.\
      \ On a failed save, a creature takes 44 (8d10) psychic damage and then becomes\
      \ vulnerable to all damage dealt by Goxomoc until the end of his next turn.\
      \ On a successful save, a creature takes half as much damage and does not become\
      \ vulnerable to damage."
    "name": "Action 3: Eruption"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/goxomoc-fleemortals.png"
```
^statblock