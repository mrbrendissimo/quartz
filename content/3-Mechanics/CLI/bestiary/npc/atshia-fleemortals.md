---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Atæshia
---
# [Atæshia](3-Mechanics\CLI\bestiary\npc/atshia-fleemortals.md)
*Source: Flee, Mortals! p. 101*  

```statblock
"name": "Atæshia (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "air, earth, fire, Leader"
"alignment": "Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "332"
"hit_dice": "35d8 + 175"
"modifier": !!int "5"
"stats":
  - !!int "19"
  - !!int "21"
  - !!int "21"
  - !!int "22"
  - !!int "23"
  - !!int "23"
"speed": "50 ft., fly 30 ft. (hover)"
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "13"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+13"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+13"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+13"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+13"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+13"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+13"
"damage_resistances": "cold, necrotic, poison, psychic, radiant"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 23"
"languages": "all"
"cr": "23"
"traits":
  - "desc": "When Atæshia fails a saving throw, a willing creature within 60 feet\
      \ of her who can see her can give their life to protect her. This creature dies\
      \ instantly, and Atæshia succeeds on the saving throw."
    "name": "Offer to Remembrance (3/Day)"
  - "desc": "When Atæshia is reduced to 0 hit points, she disintegrates into ash on\
      \ a solemn wind. For the next 100 years, if a Celestial, a Elemental, or a Humanoid\
      \ whose challenge rating or level is 5 or higher dies within 60 feet of where\
      \ Atæshia died, Atæshia returns to life where she died with 25 hit points."
    "name": "Reborn From War"
"actions":
  - "desc": "Atæshia makes three Pale Flame attacks. She can replace one attack with\
      \ a use of Moment of Loss, if available."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +13 to hit, reach 5 ft. or range 120\
      \ ft., one target. Hit: 20 (4d6 + 6) radiant damage plus 14 (4d6) fire damage.\
      \ If this attack reduces a creature to 0 hit points, they die and all their\
      \ remains burn to nothing."
    "name": "Pale Flame"
  - "desc": "Atæshia transforms one creature she can see within 60 feet of her into\
      \ the form of a living ash cloud. While transformed to ash, the target is immune\
      \ to all damage, can't provide cover to other creatures, and can't take reactions.\
      \ At the start of the target's next turn, they reform and must make a DC 21\
      \ Constitution saving throw. On a failed save, the target is reduced to 1 hit\
      \ point. On a successful save, the target takes 44 (8d10) necrotic damage. This\
      \ damage can't reduce the target's hit points below 1."
    "name": "Moment of Loss (Recharge 6)"
  - "desc": "Atæshia uses her Kindled Sacrifice villain action, even if it is unavailable,\
      \ to sacrifice herself."
    "name": "From Death, Life (1/Day)"
"bonus_actions":
  - "desc": "Atæshia forms into a cloud of ash, teleports to an unoccupied space she\
      \ can see within 60 feet of her, and reforms into her true form. Each creature\
      \ within 5 feet of the space she left must succeed on a DC 21 Dexterity saving\
      \ throw or take 5 (d10) fire damage."
    "name": "Flickering Flame"
"reactions":
  - "desc": "When another Elemental Atæshia can see within 60 feet of her is hit with\
      \ an attack, the damage from the attack is halved and the target can move up\
      \ to half their speed without provoking opportunity attacks."
    "name": "Convocation of Ash"
"legendary_actions":
  - "desc": "Atæshia has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Atæshia unleashes a pulse of overwhelming sadness. Each enemy Atæshia\
      \ can see within 120 feet of her must make a DC 21 Wisdom saving throw. On a\
      \ failed save, a creature is [dazed](/3-Mechanics/CLI/conditions.md#Dazed) for\
      \ 1 minute (save ends at end of turn). On a successful save, a creature can't\
      \ take reactions until the end of their next turn."
    "name": "Action 1: Wave of Sorrow"
  - "desc": "Atæshia chooses a willing creature within 60 feet of her to die so their\
      \ allies may live. The target dies, and up to two other dead creatures within\
      \ 60 feet of the target return to life. These revived creatures regain the same\
      \ number of hit points the sacrificed creature had, up to the revived creature's\
      \ hit point maximum."
    "name": "Action 2: Kindled Sacrifice"
  - "desc": "Atæshia releases a torrent of primordial anguish to unmake the marrow\
      \ of creation around her. Each enemy within 60 feet of her must make a DC 21\
      \ Charisma saving throw. On a failed save, they take 55 (10d10) necrotic damage\
      \ and can't regain hit points until the end of Atæshia's next turn. On a successful\
      \ save, they take half as much damage, but suffer no other effect. Succeed or\
      \ fail, if this damage reduces a creature to 0 hit points, they immediately\
      \ fail one death saving throw."
    "name": "Action 3: Life's Finale"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ataeshia-whereevillives.png"
```
^statblock