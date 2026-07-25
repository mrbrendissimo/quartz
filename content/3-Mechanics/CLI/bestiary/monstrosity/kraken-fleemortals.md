---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/solo
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kraken
---
# [Kraken](3-Mechanics\CLI\bestiary\monstrosity/kraken-fleemortals.md)
*Source: Flee, Mortals! p. 238*  

```statblock
"name": "Kraken (FleeMortals)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan, Solo"
"alignment": "Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "499"
"hit_dice": "27d20 + 216"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "26"
  - !!int "30"
  - !!int "22"
  - !!int "18"
"speed": "30 ft., swim 60 ft."
"saves":
  - "constitution": !!int "16"
  - "intelligence": !!int "18"
  - "wisdom": !!int "14"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+18"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+18"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+14"
"damage_immunities": "cold; lightning; psychic; thunder; bludgeoning, piercing, slashing\
  \ from mundane attacks"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [dazed](/3-Mechanics/CLI/conditions.md#Dazed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 24"
"languages": "understands all languages but can't speak, telepathy 150 ft."
"cr": "26"
"traits":
  - "desc": "The Kraken can breathe air and water."
    "name": "Amphibious"
  - "desc": "When the Kraken drops to 0 hit points or dies, all conditions and other\
      \ effects end for them. They teleport back to the place where they slumber,\
      \ return to life with all their hit points, and fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)."
    "name": "Discorporation"
  - "desc": "The Kraken deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "If the Kraken fails a saving throw, they can choose to succeed instead,\
      \ and their speed is reduced by a cumulative 10 feet for 24 hours."
    "name": "Slowed Resistance (3/Day)"
  - "desc": "The Kraken has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The Kraken makes four Tentacle attacks or uses Mental Lance three times."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 30 ft., one target. Hit: 19\
      \ (2d10 + 8) bludgeoning damage plus 11 (2d10) psychic damage, and the target\
      \ is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 18). The\
      \ Kraken has ten tentacles, each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "Ranged Power Attack: +18 to hit, range 120 ft., one creature. Hit:\
      \ 22 (4d10) psychic damage, and the target is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the Kraken until the start of the Kraken's next turn."
    "name": "Mental Lance (3rd-Order Power)"
  - "desc": "The Kraken creates a psionic storm, entrapping a vehicle they can see\
      \ within 120 feet of them. While entrapped in the storm, the vehicle is [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ The storm ends if the Kraken's [concentration](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ is broken (as if [concentrating](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ on a spell) or if they are more than 120 feet from the vehicle. If the Kraken's\
      \ turn ends three times before the storm ends, the vehicle is reduced to 0 hit\
      \ points and this effect ends."
    "name": "Psionic Storm"
  - "desc": "The Kraken telepathically howls in the mind of each enemy within 120\
      \ feet of them. Each target must make a DC 26 Constitution saving throw. On\
      \ a failed save, a target takes 55 (10d10) psychic damage and can't concentrate\
      \ on powers or spells until the start of the Kraken's next turn. On a successful\
      \ save, the target takes half as much damage and suffers no other effect."
    "name": "Skull-Splitting Howl (1/Day)"
"bonus_actions":
  - "desc": "The Kraken throws a creature they are grappling into an unoccupied space\
      \ the Kraken can see within 60 feet of them. The target lands [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ and takes 22 (4d10) bludgeoning damage."
    "name": "Telekinetic Fling"
"reactions":
  - "desc": "When the Kraken is damaged by an attack, each enemy within 30 feet of\
      \ the attacker (including the attacker) must make a DC 26 Wisdom saving throw,\
      \ taking 22 (4d10) psychic damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Psychic Reprisal"
"legendary_actions":
  - "desc": "The Kraken has three villain actions. They can take each action once\
      \ during an encounter after an enemy's turn. The Kraken can take these actions\
      \ in any order but can use only one per round."
    "name": ""
  - "desc": "Psionically conjured tentacles make a Tentacle attack on each enemy within\
      \ 120 feet of the Kraken. The Kraken then uses Telekinetic Fling on each creature\
      \ they are grappling."
    "name": "Action 1: Psionic Tentacles"
  - "desc": "The Kraken teleports up to 60 feet to an unoccupied space they can see.\
      \ Each creature within 30 feet of the space the Kraken left must make a DC 26\
      \ Dexterity saving throw or be covered in psionic ink, which they can use an\
      \ action to wipe away. A creature covered in psionic ink takes 16 (3d10) psychic\
      \ damage at the start of each of their turns."
    "name": "Action 2: Psionic Ink"
  - "desc": "The Kraken unleashes a wave of intense psionic power. Each creature within\
      \ 120 feet of the Kraken must make a DC 26 Wisdom saving throw. On a failed\
      \ save, a creature takes 65 (10d12) psychic damage and is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the Kraken for 1 minute (save ends at end of turn). On a successful save,\
      \ a creature takes half as much damage and isn't [frightened](/3-Mechanics/CLI/conditions.md#Frightened)."
    "name": "Action 3: The Ocean's Wrath"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/kraken-fleemortals.png"
```
^statblock