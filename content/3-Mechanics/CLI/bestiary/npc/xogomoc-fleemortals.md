---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/30
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental/solo
- ttrpg-cli/monster/type/elemental/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Xogomoc
---
# [Xogomoc](3-Mechanics\CLI\bestiary\npc/xogomoc-fleemortals.md)
*Source: Flee, Mortals! p. 237*  

```statblock
"name": "Xogomoc (FleeMortals)"
"size": "Gargantuan"
"type": "elemental"
"subtype": "titan, Solo"
"alignment": "Neutral"
"ac": !!int "20"
"hp": !!int "574"
"hit_dice": "28d20 + 280"
"modifier": !!int "10"
"stats":
  - !!int "20"
  - !!int "30"
  - !!int "30"
  - !!int "22"
  - !!int "26"
  - !!int "16"
"speed": "0 ft., fly 90 ft. (hover)"
"saves":
  - "intelligence": !!int "15"
  - "wisdom": !!int "17"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+17"
"damage_immunities": "lightning; poison; thunder; bludgeoning, piercing, slashing\
  \ from mundane attacks"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "truesight 300 ft., passive Perception 27"
"languages": "understands all languages but can't speak, telepathy 150 ft."
"cr": "30"
"traits":
  - "desc": "Xogomoc can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "When Xogomoc drops to 0 hit points or dies, all conditions and other\
      \ effects end for him. He teleports back to the place where he slumbers, transforms\
      \ into [Goxomoc](/3-Mechanics/CLI/bestiary/npc/goxomoc-fleemortals.md) with\
      \ all his hit points, and falls [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)."
    "name": "Discorporation"
  - "desc": "If Xogomoc fails a saving throw, he can choose to succeed instead, and\
      \ his Lightning Aura doesn't function until the end of his next turn."
    "name": "Disruptive Resistance (3/Day)"
  - "desc": "A creature who starts their turn within 60 feet of Xogomoc must make\
      \ a DC 25 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Lightning Aura"
  - "desc": "Lightning and thunder damage dealt by Xogomoc ignore damage resistance."
    "name": "Power of the Storm"
  - "desc": "Xogomoc deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "Xogomoc has advantage on saving throws against powers, spells, and other\
      \ supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "Xogomoc makes two Lightning Strike attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +19 to hit, reach 15 ft. or range 600\
      \ ft., one target. Hit: 29 (3d12 + 10) lightning damage, and another target\
      \ within 30 feet of the first must succeed on a DC 27 Dexterity saving throw\
      \ or take the same damage."
    "name": "Lightning Strike"
  - "desc": "Xogomoc moves up to his speed without provoking opportunity attacks.\
      \ During this move, he can move through the spaces of other creatures, and it\
      \ doesn't count as difficult terrain. The first time he moves through each creature's\
      \ space, that creature takes 22 (4d10) lightning damage."
    "name": "Energy Flow"
  - "desc": "Xogomoc breathes lightning in a 90-foot cone. Each creature in that area\
      \ must make a DC 27 Dexterity saving throw. On a failed save, a creature takes\
      \ 71 (11d12) lightning damage and can't take reactions until the end of their\
      \ next turn. On a successful save, a creature takes half as much damage and\
      \ suffers no other effect."
    "name": "Lightning Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Xogomoc teleports, along with any creatures inside him (see Into the\
      \ Storm), up to 30 feet to an unoccupied space he can see. Each creature within\
      \ 10 feet of the space he left must make a DC 25 Constitution saving throw,\
      \ taking 22 (4d10) thunder damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Gone in a Flash"
"reactions":
  - "desc": "When a creature Xogomoc can see within 30 feet of him hits him with an\
      \ attack, he encircles the attacker in bands of lightning. The creature takes\
      \ 22 (4d10) lightning damage and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until the end of their next turn."
    "name": "Shock Cage"
"legendary_actions":
  - "desc": "Xogomoc has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Xogomoc summons an aweinspiring clap of thunder. Each creature within\
      \ 120 feet of him who can hear him must succeed on a DC 25 Wisdom saving throw\
      \ or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed) for 1 minute (save ends\
      \ at end of turn)."
    "name": "Action 1: Thunderstruck"
  - "desc": "Xogomoc summons tempest winds that buffet each enemy he can see within\
      \ 30 feet of him. Each target must make a DC 25 Strength saving throw. On a\
      \ successful save, a creature takes 16 (3d10) lightning damage. On a failed\
      \ save, a creature is drawn inside"
    "name": "Action 2: Into the Storm"
  - "desc": "While inside Xogomoc, a creature is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ moves with Xogomoc, has total cover against attacks and other effects outside\
      \ Xogomoc, and takes 16 (3d10) lightning damage plus 16 (3d10) thunder damage\
      \ at the start of each of their turns.\n\nA creature inside Xogomoc can use\
      \ an action to make a DC 20 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ or Dexterity ([Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)) check to\
      \ move out of Xogomoc, entering an unoccupied space of their choice within 5\
      \ feet of Xogomoc on a success. If Xogomoc takes 60 or more damage on a single\
      \ turn or is reduced to 0 hit points, each creature inside of Xogomoc is shunted\
      \ out of him into an unoccupied space of their choice within 5 feet of Xogomoc."
    "name": "Xogomoc"
  - "desc": "Xogomoc unleashes lighting and wind in a chaotic storm. Each enemy within\
      \ 120 feet of him must make a DC 25 Strength saving throw. On a failed save,\
      \ a creature takes 44 (8d10) lightning damage and is moved up to 60 feet in\
      \ any direction. On a successful save, a creature takes half as much damage\
      \ and isn't moved."
    "name": "Action 3: Behold True Power"
"source":
  - "FleeMortals"
```
^statblock