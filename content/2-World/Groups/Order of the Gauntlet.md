---
tags:
  - Category/Group
MyContainer: "[[2-World/Regions/Faerûn.md|Faerûn]]"
MyCategory: Knightly Order
obsidianUIMode: preview
leader: Bob
officers:
  - Officer 1
  - Officer 2
members:
  - Sir Baric Nylef
initiates:
  - Initiative 1
  - Initiative 2
  - Initiative 3
faction: Faction Name 1
primary_contact: John Doe
benefits:
  - standing: 1
    reward: What do they get at level 1?
  - standing: 2
    reward: What do they get at level 2?
  - standing: 3
    reward: What do they get at level 3?
MyAllies:
  - "[[2-World/Groups/The Harpers.md|The Harpers]]"
MyEnemies:
  - "[[2-World/Groups/Cult of the Dragon.md|Cult of the Dragon]]"
---






%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE] Parent Region: `INPUT[suggester(optionQuery(#Category/Place)):MyContainer]`

> [!column|no-i no-t]
>> [!note|no-title]
>> ![[emblem_order of the gauntlet.png|300]]
>
>> [!note|div-m] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, ⁉️Goals),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!note|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Goals|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🔗Hierarchy),
> option(2, ⚡Enemies/Allies),
> option(3, 🛠️Services),
> option(4,➕Membership),
> option(5, 🛡️Ranks),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Hierarchy|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Enemies/Allies|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Services|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Membership|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Ranks|no-h clean]]

%% MAKE CHANGES BELOW THIS LINE %%

---

# General

**Select Parent:** `INPUT[suggester(optionQuery(#Category/Hub),optionQuery(#Category/Region)):MyContainer]`

**Select Category:** `INPUT[inlineSelect(option(Knightly Order), option(Religious Order), option(Magic Academy), option(Artisan Guild), option(Merchant Consortium), option(Criminal Syndicate), option(Mercenary Company), option(Noble House), option(Secret Society or Cult), option(Adventurers’ Guild)):MyCategory]`

**Values:**
- Faith is the greatest weapon against evil—faith in one’s god, one’s friends, and one’s self.
- Battling evil is an extraordinary task that requires extraordinary strength and bravery.
- Punishing an evil act is just. Punishing an evil thought is not.

Allies: [[The Harpers]] 
Enemies: [[Cult of the Dragon]]

# Goals

- Be armed and vigilant against evil.
- Identify evil threats such as secretive power groups and inherently evil creatures.
- Enforce justice.
- Enact retribution against evil actions—do not strike preemptively.

# Membership
To become a member of the Lords' Alliance faction in [[Waterdeep]], a character must be a Waterdavian citizen. Those with criminal records can also join, provided they demonstrate their allegiance to the city.

# GM Notes

The **Order of the Gauntlet** was a coalition of morally upstanding warriors, knights, paladins and clerics who dedicated themselves to the destruction of evil in Faerûn in the 15th century. They were a unified group, bonded by either their fervent religious beliefs or staunch dedication to enforcing justice in the realms. To these brothers and sisters in arms, evil had to be dealt with and could not be ignored.

Members of the order were strong in their faith, using it to stand against evil forces. While this faith ranged from believing in one's personal god, it extended also to those considered close friends, and especially to oneself. Most often, Knights of the Gauntlet venerated either the God of Guardians, Helm; two of the deities of the Triad, and as well as the Poet of Justice, Hoar.

# Hierarchy

`BUTTON[button_person]` List important relationships here. 

```dataviewjs
// 1) Grab your frontmatter arrays
const leader    = dv.current().leader    ?? null;
const officers  = dv.current().officers  ?? [];
const members   = dv.current().members   ?? [];
const initiates = dv.current().initiates ?? [];

// 2) Render the Mermaid diagram
dv.paragraph(
  "```mermaid\nflowchart LR\n" +

  // Leader node
  (leader
    ? `L[${leader}]:::internal-link\n`
    : "") +

  // Officers group
  (officers.length > 0
    ? `OG[Officers]\nL --> OG\n` +
      officers.map((o,i) =>
        `O${i+1}[${o}]:::internal-link\nOG --> O${i+1}\n`
      ).join("")
    : "") +

  // Members group
  (members.length > 0
    ? `MG[Members]\n${officers.length ? "OG" : "L"} --> MG\n` +
      members.map((m,i) =>
        `M${i+1}[${m}]:::internal-link\nMG --> M${i+1}\n`
      ).join("")
    : "") +

  // Initiates group
  (initiates.length > 0
    ? `IG[Initiates]\n${members.length ? "MG" : (officers.length ? "OG" : "L")} --> IG\n` +
      initiates.map((n,i) =>
        `I${i+1}[${n}]:::internal-link\nIG --> I${i+1}\n`
      ).join("")
    : "") +

  "```"
)
```

> [!NOTE]- Relationship Config - Enter name of People Notes
> | Leader    | Officers    | 
> | --- | --- | 
> | `INPUT[list:leader]`    | `INPUT[list:officers]`    | 
> 
> | Members    | Initiates    | 
> | --- | --- | 
> | `INPUT[list:members]`    | `INPUT[list:initiates]`    |

# Enemies/Allies
**Enemies:** `INPUT[inlineListSuggester(optionQuery(#Category/Group),optionQuery(#Category/People)):MyEnemies]`

**Allies:** `INPUT[inlineListSuggester(optionQuery(#Category/Group),optionQuery(#Category/People)):MyAllies]`

# People

The following people are members of this group.  

```dataview
TABLE WITHOUT ID link(file.name) AS "Name", char_race AS "Race", char_gender AS "Gender"
FROM "2-Campaign/Quests"
WHERE contains(Connected_Groups, this.file.link)
SORT file.name ASC
```


```base
properties:
  property.char_age:
    displayName: Age
  property.char_gender:
    displayName: Gender
  property.char_race:
    displayName: Race
  property.char_status:
    displayName: Status
  file.name:
    displayName: Name
  note.char_status:
    displayName: Status
  note.char_race:
    displayName: Race
  note.char_gender:
    displayName: Gender
  note.char_age:
    displayName: Age Range
views:
  - type: table
    name: People
    filters:
      and:
        - file.inFolder("2-World/People")
        - MyContainer.contains(this.file.path)
    order:
      - file.name
      - MyContainer
      - MyCategory
      - char_status
      - char_race
      - char_gender
      - char_age
    sort:
      - column: note.char_race
        direction: ASC
      - column: note.MyContainer
        direction: ASC
      - column: file.name
        direction: ASC
    columnSize:
      file.name: 177
      note.MyCategory: 221
      note.MyContainer: 244
      note.char_status: 137
      note.char_race: 160
      note.char_gender: 143
      note.char_age: 149

```


# Services

Services offered. 


> [!NOTE]+ Public Services
> | Item   | Cost | Weight |
> | ------ | ---- | ------ |
> | Service 1 | 1gp  | L      |
> | Service 2 | 1cp  | -      |

> [!NOTE]- Member Services
> | Item   | Cost | Weight |
> | ------ | ---- | ------ |
> | Service 1 | 1gp  | L      |
> | Service 2 | 1cp  | -      |

# Ranks

### **RANK 1:** **Chevall (1 Renown)**[](https://auth.fandom.com/signin?redirect=https%3A%2F%2Ftravelogue.fandom.com%2Fwiki%2FThe_Order_of_the_Gauntlet%3Fveaction%3Dedit%26section%3D5&uselang=en "Sign in to edit")

This is the rank a character receives when first joining the Order of the Gauntlet. For more information on the general benefits of this rank, refer to [Factions](https://travelogue.fandom.com/wiki/Factions "Factions").

**Receive Your Faction's Insignia.** The insignia for the Order of the Gauntlet is a silver pendant depicting the blade of retribution held in place by the gauntlet of justice.

### **RANK 2: Marcheon (3 Renown)**[](https://auth.fandom.com/signin?redirect=https%3A%2F%2Ftravelogue.fandom.com%2Fwiki%2FThe_Order_of_the_Gauntlet%3Fveaction%3Dedit%26section%3D6&uselang=en "Sign in to edit")

Marcheons have shown that they are aligned with the Order's goals, and can take on more responsibility. For more information on the general benefits of this rank, refer to [Factions](https://travelogue.fandom.com/wiki/Factions "Factions").

**Faction Training.** The Order of the Gauntlet offers training in Smith’s tools, Leatherworker’s tools, Carpenter’s tools, Mason’s tools, or Vehicles.

### **RANK 3: Whitehawk (10 Renown)**[](https://auth.fandom.com/signin?redirect=https%3A%2F%2Ftravelogue.fandom.com%2Fwiki%2FThe_Order_of_the_Gauntlet%3Fveaction%3Dedit%26section%3D7&uselang=en "Sign in to edit")

Whitehawks are reliable faction agents, entrusted with many secrets and deserving of additional support during adventures. For more information on the general benefits of this rank, refer to [Factions](https://travelogue.fandom.com/wiki/Factions "Factions").

**Item Procurement.** The Order of the Gauntlet can procure the following items for a Whitehawk:

- Uncommon rarity: _+1 weapon or +1 shield, cloak of protection_
- Rare rarity: _+1 armor, ring of warmth_

### **RANK 4: Vindicator (25 Renown)**[](https://auth.fandom.com/signin?redirect=https%3A%2F%2Ftravelogue.fandom.com%2Fwiki%2FThe_Order_of_the_Gauntlet%3Fveaction%3Dedit%26section%3D8&uselang=en "Sign in to edit")

Vindicators are trusted voices within the Order of the Gauntlet. They are looked up as champions of the Order. For more information on the general benefits of this rank, refer to [Factions](https://travelogue.fandom.com/wiki/Factions "Factions").

**Becoming a Mentor.** The Order of the Gauntlet can requisition a **veteran of the gauntlet** or **priest of the gauntlet** to serve the Vindicator.