---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Yakfolk Priest
---
# [Yakfolk Priest](3-Mechanics\CLI\bestiary\monstrosity/yakfolk-priest-skt.md)
*Source: Storm King's Thunder p. 245*  

Yakfolk, known among themselves as Yikaria ("the Lucky Chosen" in their language), are ogre-sized bipeds with curved horns and dour expressions. Their hulking bodies are coated with thick fur and hair, and many outsiders can't tell the males and females apart.

## Servants of the Forgotten God

Yakfolk are the creations of a malevolent deity they call the Forgotten God. The worship of this nameless deity directs their lives. The deity takes the form of a male Yikaria, but its face is worn smooth into a featureless mask. The deity is appeased by sacrifice, which its followers carry out by capturing Humanoids and putting them to death by fire (immolation), earth (live burial), water (drowning), or air (throwing the victims off a great height). Sacrifices ensure the Forgotten God's benevolence.

The Forgotten God enabled the yakfolk to enslave dao for a time. It is said that the Forgotten God journeyed to the Elemental Plane of Earth and, through guile and deception, defeated the Grand Khan of the dao. The price of that defeat was harsh: the dao were forced to serve the Forgotten God and its minions—and forbidden to attack them—"for a thousand years and a year." The sentence has since expired, and yakfolk can no longer summon dao as they once did, but fear of the Forgotten God has kept the dao from seeking vengeance.

## Yakfolk Society

Yakfolk dwell in secluded settlements sheltered from the worst of nature's abuse, including mountain valleys, soaring plateaus, and desert oases. Outsiders that stumble into an enclave of yakfolk are usually surprised and pleased to find what appears to be a utopia, and the yakfolk foster that image until the strangers can be disarmed and taken prisoner.

In their seemingly idyllic hideaways, the yakfolk rule with iron fists, and for all their learning and culture, they are enormously evil overlords. Yakfolk care for their hapless prisoners only to the extent that a live one is more useful than a dead one, and putting a prisoner to work is easier than laboring oneself. It's not that yakfolk are lazy—quite the contrary. They simply consider most menial tasks beneath them.

Yakfolk have a drive for learning, particularly when it comes to the secrets of elemental magic and dark knowledge that might serve to corrupt or dominate others. Knowledge that the yakfolk can't gain or use is to be destroyed. Unsentimental by nature, yakfolk parents pack children off to communal creches once they are weaned, never to recognize them again. Yakfolk feel no loyalty to their families—only to their god and race.

## Skin Crawlers

A yakfolk's most frightening weapon is its ability to magically crawl under another creature's skin, control its body, and suppress its mind. The yakfolk use this ability to spy on enemies, rob them, murder their leaders, and kidnap their young.

```statblock
"name": "Yakfolk Priest (SKT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "15"
  - !!int "14"
  - !!int "18"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "passive Perception 14"
"languages": "Common, Yikaria"
"cr": "4"
"traits":
  - "desc": "The yakfolk is a 7th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 14, +6 to hit with spell attacks). The priest has the following\
      \ cleric spells prepared:\n\nCantrips (at will): [light](/3-Mechanics/CLI/spells/light-xphb.md),\
      \ [mending](/3-Mechanics/CLI/spells/mending-xphb.md), [sacred flame](/3-Mechanics/CLI/spells/sacred-flame-xphb.md),\
      \ [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\n1st level\
      \ (4 slots): [bane](/3-Mechanics/CLI/spells/bane-xphb.md), [command](/3-Mechanics/CLI/spells/command-xphb.md),\
      \ [cure wounds](/3-Mechanics/CLI/spells/cure-wounds-xphb.md), [sanctuary](/3-Mechanics/CLI/spells/sanctuary-xphb.md)\n\
      \n2nd level (3 slots): [augury](/3-Mechanics/CLI/spells/augury-xphb.md),\
      \ [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [spiritual weapon](/3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\n\
      \n3rd level (3 slots): [bestow curse](/3-Mechanics/CLI/spells/bestow-curse-xphb.md),\
      \ [protection from energy](/3-Mechanics/CLI/spells/protection-from-energy-xphb.md),\
      \ [sending](/3-Mechanics/CLI/spells/sending-xphb.md)\n\n4th level (1 slots):\
      \ [banishment](/3-Mechanics/CLI/spells/banishment-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The yakfolk attempts to magically possess a humanoid or giant. The yakfolk\
      \ must touch the target throughout a short rest, or the attempt fails. At the\
      \ end of the rest, the target must succeed on a DC 12 Constitution saving throw\
      \ or be possessed by the yakfolk, which disappears with everything it is carrying\
      \ and wearing. Until the possession ends, the target is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ loses control of its body, and is unaware of its surroundings. The yakfolk\
      \ now controls the body and can't be targeted by any attack, spell, or other\
      \ effect, and it retains its alignment; its Intelligence, Wisdom, and Charisma\
      \ scores; and its proficiencies. It otherwise uses the target's statistics,\
      \ except the target's knowledge, class features, feats, and proficiencies.\n\
      \nThe possession lasts until either the body drops to 0 hit points, the yakfolk\
      \ ends the possession as an action, or the yakfolk is forced out of the body\
      \ by an effect such as the [dispel evil and good](/3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md)\
      \ spell. When the possession ends, the yakfolk reappears in an unoccupied space\
      \ within 5 feet of the body and is [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ until the end of its next turn. If the host body dies while it is possessed\
      \ by the yakfolk, the yakfolk dies as well, and its body doesn't reappear."
    "name": "Possession (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The yakfolk makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
      \ (2d6 + 3) bludgeoning damage, or 12 (2d8 + 3) bludgeoning damage if used with\
      \ two hands."
    "name": "Quarterstaff"
  - "desc": "The yakfolk summons an [earth elemental](/3-Mechanics/CLI/bestiary/elemental/earth-elemental-xmm.md).\
      \ The elemental appears in an unoccupied space within 60 feet of its summoner\
      \ and acts as an ally of the summoner. It remains for 10 minutes, until it dies,\
      \ or until its summoner dismisses it as an action."
    "name": "Summon Earth Elemental (1/Day)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/yakfolk-priest-skt.webp"
```
^statblock