---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Forzaantirilys
---
# [Forzaantirilys](3-Mechanics\CLI\bestiary\npc/forzaantirilys-fleemortals.md)
*Source: Flee, Mortals! p. 79*  

```statblock
"name": "Forzaantirilys (FleeMortals)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "585"
"hit_dice": "30d20 + 270"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "10"
  - !!int "28"
  - !!int "19"
  - !!int "16"
  - !!int "22"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "constitution": !!int "16"
  - "wisdom": !!int "10"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+17"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
"damage_immunities": "fire, radiant"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 120 ft., truesight 60 ft., passive Perception 20"
"languages": "Common, Draconic"
"cr": "24"
"traits":
  - "desc": "Fire damage dealt by Forzaantirilys ignores damage resistance."
    "name": "Hellfire"
  - "desc": "When Forzaantirilys fails a saving throw, she can succeed instead. When\
      \ she does, attack rolls made against her have advantage until the end of her\
      \ next turn."
    "name": "Ireful Defense (3/Day)"
"actions":
  - "desc": "Forzaantirilys makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 21\
      \ (2d10 + 10) piercing damage plus 14 (4d6) fire damage, and the target is set\
      \ on fire for 1 minute or until the target or a creature who can reach them\
      \ uses an action to extinguish the flames. A creature who is on fire at the\
      \ start of their turn takes 10 (3d6) fire damage. If a creature who is already\
      \ on fire is set on fire again on a subsequent turn, the damage isn't cumulative,\
      \ but the duration of the fire resets to 1 minute."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 17\
      \ (2d6 + 10) slashing damage, and Forzaantirilys can move the target up to 15\
      \ feet horizontally."
    "name": "Claw"
  - "desc": "Forzaantirilys exhales fire in a 90-foot cone. Each creature in that\
      \ area must make a DC 24 Dexterity saving throw. On a failed save, a creature\
      \ takes 70 (20d6) fire damage, and any mundane metal objects they are wearing\
      \ or carrying are melted into slag and destroyed. On a successful save, a creature\
      \ takes half as much damage and their equipment isn't destroyed.\n\nAdditionally,\
      \ the fire remains in that area until the end of Forzaantirilys's next turn.\
      \ For the duration, that area is difficult terrain, and a creature who enters\
      \ that area for the first time on a turn or ends their turn there takes 14 (4d6)\
      \ fire damage."
    "name": "Scorching Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Forzaantirilys moves up to half her speed. If she enters a creature's\
      \ space during this move, the creature takes 10 (3d6) fire damage."
    "name": "Blazing Rush"
"reactions":
  - "desc": "When a creature within 120 feet of Forzaantirilys attacks her, the attacker\
      \ must make a DC 21 Dexterity saving throw. On a failed save, the attacker is\
      \ set on fire for 1 minute or until the attacker or a creature who can reach\
      \ them uses an action to extinguish the flames. A creature who is on fire at\
      \ the start of their turn takes 10 (3d6) fire damage. If a creature who is already\
      \ on fire is set on fire again on a subsequent turn, the damage isn't cumulative,\
      \ but the duration of the fire resets to 1 minute."
    "name": "Ignite the Insolent"
"legendary_actions":
  - "desc": "Forzaantirilys has three villain actions. She can take each action once\
      \ during an encounter after an enemy's turn. She can take these actions in any\
      \ order but can use only one per round."
    "name": ""
  - "desc": "A 30-foot-radius cloud of smoke and cinders surrounds Forzaantirilys\
      \ until the end of her next turn. That area is heavily obscured for creatures\
      \ other than Forzaantirilys. An enemy who needs to breathe and starts their\
      \ turn within the cloud must succeed on a DC 21 Constitution saving throw or\
      \ be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) for 1 minute (save\
      \ ends at end of turn)."
    "name": "Action 1: Cinderfall"
  - "desc": "Forzaantirilys's skin hardens into a protective armor of ashen scales,\
      \ granting her 100 temporary hit points. Until all these temporary hit points\
      \ are gone, a creature within 5 feet of Forzaantirilys who touches her or hits\
      \ her with an attack takes 14 (4d6) fire damage."
    "name": "Action 2: Ashen Armor"
  - "desc": "Forzaantirilys unleashes a massive burst of light and heat. Each creature\
      \ within 120 feet of her must make a DC 21 Constitution saving throw. On a failed\
      \ save, a creature takes 35 (10d6) fire damage plus 35 (10d6) radiant damage\
      \ and is [blinded](/3-Mechanics/CLI/conditions.md#Blinded). On a successful\
      \ save, a creature takes half as much damage and isn't [blinded](/3-Mechanics/CLI/conditions.md#Blinded).\
      \ The blindness lasts until cured by a power, a spell, or a similar supernatural\
      \ effect that removes the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ condition."
    "name": "Action 3: Supernova"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/forzaantilirys-whereevillives.png"
```
^statblock