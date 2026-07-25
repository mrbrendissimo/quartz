---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vampire
---
# [Vampire](3-Mechanics\CLI\bestiary\undead/vampire-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 270*  

```statblock
"name": "Vampire (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "Skirmisher"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "5"
"stats":
  - !!int "20"
  - !!int "20"
  - !!int "18"
  - !!int "18"
  - !!int "16"
  - !!int "20"
"speed": "30 ft., fly 30 ft."
"saves":
  - "dexterity": !!int "10"
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+10"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from mundane attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 18"
"languages": "the languages they knew in life"
"cr": "13"
"traits":
  - "desc": "In addition to any other spells in this stat block, the vampire can cast\
      \ the following spells, using Charisma as the spellcasting ability (spell save\
      \ DC 18):\n\nAt will: [charm person](/3-Mechanics/CLI/spells/charm-person-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [disguise self](/3-Mechanics/CLI/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [sending](/3-Mechanics/CLI/spells/sending-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n1/day each: [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [geas](/3-Mechanics/CLI/spells/geas-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "Each time the vampire takes radiant damage, they take an extra 10 radiant\
      \ damage."
    "name": "Radiant Aversion"
  - "desc": "When the vampire drops to 0 hit points and is not in sunlight, running\
      \ water, or their resting place, the vampire teleports to their resting place.\
      \ While in their resting place, the vampire is stable. After spending 1 hour\
      \ in their resting place with 0 hit points, they regain 1 hit point."
    "name": "Resting Place"
  - "desc": "The vampire has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "The vampire makes two Claw attacks and, if possible, a Bite attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage. If the target is\
      \ Large or smaller, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 18). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ Moving while grappling a Medium or smaller creature doesn't halve the vampire's\
      \ speed. A vampire can have only one target [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way at a time."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one creature who is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the vampire, [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained). Hit: 8 (1d6\
      \ + 5) piercing damage plus 10 (3d6) necrotic damage. The target's hit point\
      \ maximum is reduced by a number equal to the necrotic damage taken, and the\
      \ vampire regains hit points equal to that number. The reduction lasts until\
      \ reversed by a cure ailment power of 4th order or higher, a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect. The target dies if this attack reduces\
      \ their hit point maximum to 0. A Humanoid slain in this way rises the following\
      \ midnight as a vampire spawn under the vampire's control."
    "name": "Bite"
  - "desc": "The vampire, along with anything they are wearing or carrying, turns\
      \ into a cloud of blood-sucking mist. When they do, they release any creature\
      \ they were grappling, and if the vampire was [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained), that effect ends\
      \ for them. Then the vampire flies up to twice their speed to an unoccupied\
      \ space. During this move, the vampire ignores difficult terrain, doesn't provoke\
      \ opportunity attacks, and can move through creatures and objects. Each creature\
      \ the vampire passes through must make a DC 18 Constitution saving throw, taking\
      \ 35 (10d6) necrotic damage on a failed save, or half as much damage on a successful\
      \ one. At the end of this movement, the vampire transforms back into their previous\
      \ form."
    "name": "Exsanguinating Mist (Recharge 6)"
"bonus_actions":
  - "desc": "The vampire targets one creature they can see within 30 feet of them\
      \ and who can see them. The target must make a DC 18 Wisdom saving throw. On\
      \ a failed save, the target uses their reaction, if available, to move up to\
      \ their speed to a location chosen by the vampire, then either makes a melee\
      \ attack against a target of the vampire's choice or falls [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ (vampire's choice).\n\nCreatures who can't be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ automatically succeed on this saving throw, and creatures who have advantage\
      \ on saving throws against being [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ make this saving throw with advantage."
    "name": "Beguile"
  - "desc": "The vampire moves up to their speed without provoking opportunity attacks."
    "name": "Inhuman Agility"
"reactions":
  - "desc": "When an ally the vampire can see takes damage, the vampire can command\
      \ the ally to move up to their speed without provoking opportunity attacks."
    "name": "Run, My Child"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
```
^statblock