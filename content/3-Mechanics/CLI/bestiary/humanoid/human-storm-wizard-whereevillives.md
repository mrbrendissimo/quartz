---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Storm Wizard
---
# [Human Storm Wizard](3-Mechanics\CLI\bestiary\humanoid/human-storm-wizard-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 164*  

```statblock
"name": "Human Storm Wizard (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Controller"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "16"
  - !!int "18"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+7"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "6"
"traits":
  - "desc": "In addition to any other spells in this stat block, the wizard can cast\
      \ the following spells, using Intelligence as the spellcasting ability (spell\
      \ save DC 15):\n\nAt will: [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n1/day each: [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [see invisibility](/3-Mechanics/CLI/spells/see-invisibility-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [sending](/3-Mechanics/CLI/spells/sending-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "When the wizard makes an attack, they have advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. Hit: 21 (6d6) lightning damage."
    "name": "Arcane Staff"
  - "desc": "A 10-foot-wide, 60-foot-long line of strong wind gusts from the wizard\
      \ for 1 minute. Each creature who starts their turn in that area must succeed\
      \ on a DC 15 Strength saving throw or be pushed 15 feet away from the wizard.\
      \ Each creature in that area must spend 2 feet of movement for every 1 foot\
      \ they move toward the wizard.\n\nThe gust disperses gas or vapor, and it extinguishes\
      \ candles, torches, and similar unprotected flames. It has a 50 percent chance\
      \ to extinguish protected flames like lanterns. The wizard can use a bonus action\
      \ to change the direction in which the wind blasts from them."
    "name": "Gust of Wind (1/Day; 2nd-Level Spell; Concentration)"
  - "desc": "The wizard fires magical lightning in a 5-foot-wide, 100-foot-long line.\
      \ Each creature in the line must make a DC 15 Dexterity saving throw, taking\
      \ 28 (8d6) lightning damage on a failed save, or half as much damage on a successful\
      \ one. The lightning ignites flammable objects in the area that aren't being\
      \ worn or carried."
    "name": "Lightning Bolt (3/Day; 3rd-Level Spell)"
"reactions":
  - "desc": "When the wizard is hit by an attack, they magically gain a +5 bonus to\
      \ AC against that attack, potentially causing it to miss. If the attacker is\
      \ within 10 feet of the wizard, the attacker must succeed on a DC 15 Constitution\
      \ saving throw or take 18 (4d8) thunder damage and be pushed 10 feet away from\
      \ the wizard."
    "name": "Arcane Shield (3/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/human-storm-wizard-fleemortals.png"
```
^statblock