---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ithu'rath
---
# [Ithu'rath](3-Mechanics\CLI\bestiary\npc/ithurath-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 132, Flee, Mortals! p. 202*  

```statblock
"name": "Ithu'rath (WhereEvilLives)"
"size": "Large"
"type": "aberration"
"subtype": "Solo"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "255"
"hit_dice": "30d10 + 90"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "9"
  - !!int "16"
  - !!int "23"
  - !!int "14"
  - !!int "18"
"speed": "30 ft., fly 60 ft. (hover), swim 60 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "11"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [flanked](/3-Mechanics/CLI/conditions.md#Flanked),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 22"
"languages": "Common, Deep Speech, Undercommon, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "Ithu'rath can breathe air and water."
    "name": "Amphibious"
  - "desc": "Ithu'rath is immune to any power, spell, or effect that would alter their\
      \ form."
    "name": "Immutable Form"
  - "desc": "When Ithu'rath fails a saving throw, they can succeed on the save by\
      \ channeling the power of their protective slime. Until the end of Ithu'rath's\
      \ next turn, creatures have advantage on the saving throw for Ithu'rath's Devolving\
      \ Tentacle attack."
    "name": "Slimy Resistance (3/Day)"
  - "desc": "Ithu'rath has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "Ithu'rath makes six Devolving Tentacle attacks and uses Piscine Transformation."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 20 ft., one target. Hit: 16\
      \ (3d6 + 6) piercing damage. The first time a creature is hit with this attack\
      \ on a turn, they must succeed on a DC 19 Constitution saving throw or be injected\
      \ with a degenerative psionic slime (save ends at end of turn). While slimed,\
      \ each time the creature makes an attack roll or an ability check, they must\
      \ roll a d4 and subtract the number rolled from the d20 roll. At the end of\
      \ a slimed creature's turn, the size of the subtracted die increases by one:\
      \ the d4 becomes a d6, the d6 becomes a d8, and so on, to a maximum of d12.\
      \ The cure ailment power or [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell also ends this effect."
    "name": "Devolving Tentacle"
  - "desc": "Ithu'rath targets a creature with a head, legs, or torso they can see\
      \ within 60 feet of them, blasting them with a pulse of transformational energy.\
      \ The target must succeed on a DC 19 Wisdom saving throw or undergo one of the\
      \ following transformations of the Ithu'rath's choice:\n\n- Head. The target's\
      \ head transforms into the head of a fish, proportionately sized for their body.\
      \ They can't speak.  \n- Legs. The target's legs become fins. Their walking\
      \ speed is reduced to 10 feet (unless their walking speed is slower), and they\
      \ gain a swimming speed of 30 feet.  \n- Torso. The target's torso becomes\
      \ the body of a fish with gills. They can only breathe water and can hold their\
      \ breath for 1 hour. If the target isn't underwater when this transformation\
      \ takes effect, they begin suffocating.  \n\nThe transformation lasts until\
      \ a cure ailment power of 4th order or higher or the [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell affects the target. A target who suffers all three transformations at\
      \ once is permanently transformed into a hybrid fishlike creature and can only\
      \ be returned to their original form by a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell or similar supernatural effects."
    "name": "Piscine Transformation (3rd-Order Power)"
"bonus_actions":
  - "desc": "Ithu'rath teleports 30 feet to an unoccupied space they can see."
    "name": "Jaunt (3rd-Order Power)"
"reactions":
  - "desc": "When a creature within 30 feet of Ithu'rath hits them with an attack,\
      \ Ithu'rath can psionically barrage that creature. That creature must succeed\
      \ on a DC 19 Constitution saving throw or be pushed 5 feet away from Ithu'rath\
      \ and be [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until the end\
      \ of the creature's next turn, as their lower body temporarily melts into an\
      \ immovable goo."
    "name": "Liquefy (3rd-Order Power)"
"legendary_actions":
  - "desc": "Ithu'rath has three villain actions. They can take each action once during\
      \ an encounter after an enemy's turn. They can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Ithu'rath targets one or more creatures with a skeleton within 60 feet\
      \ of them, attempting to temporarily melt their ligaments. Each target must\
      \ succeed on a DC 19 Constitution saving throw or take 18 (4d8) necrotic damage\
      \ and have disadvantage on Strength- and Dexterity-based ability checks, attack\
      \ rolls, and saving throws for 1 minute (save ends at end of turn)."
    "name": "Action 1: Skeletal Collapse"
  - "desc": "Ithu'rath channels a pulse of telekinetic energy to scour and harry their\
      \ foes. Each enemy within 60 feet of Ithu'rath must succeed on a DC 19 Strength\
      \ saving throw or take 18 (4d8) force damage and be moved up to 30 feet in any\
      \ direction."
    "name": "Action 2: Psychic Pulse"
  - "desc": "Ithu'rath unleashes a cloud of transformative slime. Each creature within\
      \ 60 feet of Ithu'rath who isn't an olothec or a slime servant must make a DC\
      \ 19 Constitution saving throw. On a failed save, a target takes 45 (10d8) piercing\
      \ damage and is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until the\
      \ end of their next turn as their eyes temporarily turn into insectoid feelers.\
      \ On a successful save, a target takes half as much damage and isn't [blinded](/3-Mechanics/CLI/conditions.md#Blinded)."
    "name": "Action 3: Slime Storm"
"lair_actions":
  - "desc": "When fighting inside their lair, Ithu'rath can take lair actions. On\
      \ initiative count 20 (losing initiative ties), Ithu'rath can take one lair\
      \ action to cause one of the following effects; Ithu'rath can't use the same\
      \ lair action two rounds in a row:"
    "name": ""
  - "desc": "- Baleful Teleport. A surge of psionic power scours up to two creatures\
      \ Ithu'rath can see within 60 feet of Ithu'rath. Each creature must succeed\
      \ on a DC 15 Charisma saving throw or be teleported up to 60 feet to an unoccupied\
      \ space the olothec can see.  \n- Psychic Shock. Ithu'rath targets up to\
      \ two creatures within 30 feet of them who are under the slime effect of Ithu'rath's\
      \ Devolving Tentacle. Each target takes 9 (2d8) psychic damage and Ithu'rath\
      \ regains a number of hit points equal to the total damage taken.  \n- Slime\
      \ Eruption. A surge of toxic slime erupts from tunnels or caverns, targeting\
      \ up to three creatures within 120 feet of Ithu'rath. Each target must succeed\
      \ on a DC 15 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of their next turn.  "
    "name": ""
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ithurath-whereevillives.png"
```
^statblock