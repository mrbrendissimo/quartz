---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Count Rhodar von Glauer
---
# [Count Rhodar von Glauer](3-Mechanics\CLI\bestiary\undead/count-rhodar-von-glauer-fleemortals.md)
*Source: Flee, Mortals! p. 272*  

```statblock
"name": "Count Rhodar von Glauer (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Solo"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "289"
"hit_dice": "34d8 + 136"
"modifier": !!int "5"
"stats":
  - !!int "23"
  - !!int "20"
  - !!int "18"
  - !!int "20"
  - !!int "17"
  - !!int "22"
"speed": "30 ft., fly 30 ft."
"saves":
  - "dexterity": !!int "11"
  - "wisdom": !!int "9"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+12"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+11"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+12"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+11"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from mundane attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 19"
"languages": "Common"
"cr": "19"
"traits":
  - "desc": "In addition to any other spells in this stat block, Rhodar can cast the\
      \ following spells, using Charisma as the spellcasting ability (spell save DC\
      \ 20):\n\nAt will: [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [sending](/3-Mechanics/CLI/spells/sending-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n3/day each: [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [geas](/3-Mechanics/CLI/spells/geas-xphb.md) (at 9th level) <sup>[+](#^superscript-casting-time)</sup>,\
      \ [legend lore](/3-Mechanics/CLI/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "When Rhodar drops to 0 hit points and isn't in his resting place, he\
      \ teleports to his resting place. While in his resting place, Rhodar is stable.\
      \ After spending 1 hour in his resting place with 0 hit points, he regains 1\
      \ hit point."
    "name": "Resting Place"
  - "desc": "Rhodar is surrounded by three floating spears of shimmering darkness,\
      \ which he can summon to a free hand on his turn (no action required). When\
      \ Rhodar fails an ability check or saving throw, he can choose to destroy one\
      \ of these spears and succeed on the ability check or saving throw instead.\
      \ Once Rhodar destroys all three spears, he can't use his Spear of the Damned\
      \ attack or Spear Sacrifice until the next dusk, when he manifests any destroyed\
      \ spears."
    "name": "Spear Sacrifice (3/Day)"
"actions":
  - "desc": "Rhodar makes two Sanguinus attacks, and he can make one Spear of the\
      \ Damned attack for each Spear Sacrifice use he has remaining."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d6 + 6) slashing damage plus 14 (4d6) necrotic damage. If the target is\
      \ a creature, their hit point maximum is reduced by a number equal to the necrotic\
      \ damage taken, and Rhodar regains hit points equal to that number. This reduction\
      \ lasts until reversed by a cure ailment power of 4th order or higher, a [greater\
      \ restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md) spell, or\
      \ a similar supernatural effect.\n\nThe target dies if this effect reduces their\
      \ hit point maximum to 0. A humanoid slain in this way rises the following midnight\
      \ as a vampire spawn under Rhodar's control."
    "name": "Sanguinus"
  - "desc": "Ranged Spell Attack: +12 to hit, range 60 ft., one target. Hit: 10\
      \ (3d6) force damage, and if the target is a creature, they are knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained) as a spear of\
      \ darkness impales them. A creature can attempt to free themself or another\
      \ creature within their reach by using an action or a bonus action to make a\
      \ DC 20 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check.\
      \ On a success, the creature is freed and the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition ends for them. The creature is also freed if Rhodar summons that\
      \ spear to attack another target or destroys it using Spear Sacrifice."
    "name": "Spear of the Damned"
"bonus_actions":
  - "desc": "Rhodar targets one creature he can see within 30 feet of him and who\
      \ can see him. The target must make a DC 20 Wisdom saving throw. On a failed\
      \ save, the creature uses their reaction, if available, to move up to their\
      \ speed to a location chosen by Rhodar, then either makes a melee attack against\
      \ a target of Rhodar's choice or falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ (Rhodar's choice)."
    "name": "Beguile"
  - "desc": "Rhodar moves up to his speed without provoking opportunity attacks."
    "name": "Inhuman Agility"
"reactions":
  - "desc": "When Rhodar is hit by an attack by a creature he can see within 60 feet\
      \ of him, his eyes bore into the creature. The target must succeed on a DC 20\
      \ Wisdom saving throw or take 10 (3d6) necrotic damage."
    "name": "Withering Stare"
"legendary_actions":
  - "desc": "Rhodar has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Rhodar causes blood to explode in a 20-foot-radius sphere centered on\
      \ a point he can see within 120 feet of him. Creatures who aren't Undead in\
      \ that area must succeed on a DC 20 Dexterity saving throw or be bloodstained\
      \ until the end of Rhodar's next turn. Rhodar has advantage on attack rolls\
      \ against bloodstained creatures, and bloodstained creatures have disadvantage\
      \ on saving throws against Rhodar's Beguile bonus action."
    "name": "Action 1: Bloodstained"
  - "desc": "Rhodar, along with anything he is wearing or carrying, turns into a Large\
      \ dragon made of fire. When he does, he releases any creature he was grappling,\
      \ and if Rhodar was [grappled](/3-Mechanics/CLI/conditions.md#Grappled) or [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ that effect ends for him. He then flies up to twice his speed to an unoccupied\
      \ space. During this move, Rhodar ignores difficult terrain, doesn't provoke\
      \ opportunity attacks, and can move through creatures and objects. Each creature\
      \ Rhodar passes through must make a DC 20 Dexterity saving throw, taking 36\
      \ (8d8) fire damage on a failed save, or half as much damage on a successful\
      \ one. At the end of this movement, Rhodar transforms back into his previous\
      \ form."
    "name": "Action 2: Fire Drake"
  - "desc": "Rhodar fills the area within 60 feet of him with thick swirling mists,\
      \ heavily obscuring that area for other creatures. He can teleport up to four\
      \ times into any unoccupied space in the mist and make one Sanguinus attack\
      \ after each teleport. The mist dissipates at the end of this action."
    "name": "Action 3: Mist of Blades"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/undead/token/count-rhodar-von-glauer-whereevillives.png"
```
^statblock