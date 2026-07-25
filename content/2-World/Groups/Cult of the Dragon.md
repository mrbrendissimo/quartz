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
  - Member 1
  - Member 2
  - Member 3
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
MyEnemies:
  - "[[Order of the Gauntlet|Order of the Gauntlet]]"
  - "[[2-World/Groups/Zhentarim.md|Zhentarim]]"
---






%% DO NOT MAKE CHANGES TO THIS PART OF THE TEMPLATE %%

> [!NOTE] Parent Region: `INPUT[suggester(optionQuery(#Category/Place)):MyContainer]`

> [!column|no-i no-t]
>> [!note|no-title]
>> ![[emblem_cult_of_the_dragon.jpg|500]]
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

**Values:** The exact beliefs of the Cult and its members are unknown outside of the group and often differ within cells of the organization. They are known to revere Dragons, especially Chromatic Dragons, as majestic and wise creatures.

The Cult of the Dragon is a secretive society of people dedicated to the worship of Dragonkind. Their reverence of Dragons borders on the semi-religious. The society is considered to be evil by most people who have heard of it but those within the group consider it as persecution for their faith in deities other than the usual Gods and hence the need for secrecy.

Due to the clandestine nature of the organization, information regarding them is often based on nothing more than rumour unless it comes direct from experiences with members.

Allies / Enemies:

Membership Requirements:

Benefits This crime syndicate can protect its members from the consequences of all but the most heinous crimes.
Rank 1: borrow resources (100 gp), case (+15), diversion (+15), gather information, lookout (4 ways, +15)
Rank 2: borrow resources (1,000 gp), put in a good word, remove evidence, rob, search black market
Rank 3: borrow resources (5,000 gp), command team (1d4 NPCs of 3rd level, or 3d4 NPCs of 1st level), destroy evidence, market manipulation, reciprocal benefits Rank 4: black market mastery, borrow resources (15,000 gp), command team (1d4 NPCs of 6th level, or 5d4 NPCs of 3rd level)

# Goals

The goals of the cult are unknown to those outside of its society. Rumours persist that they work to bring a Dragon controlled world into being as well as revive dead dragons.

# Membership
To join the group, a PC must spend X week 'doing' something, or 'something else'.

# GM Notes

As a secretive group the Cult doesn't display icons overtly in order to mask their presence. They do however have a symbol they use with each other, that of a dragon skull made of flame above claws, while cultists wear a uniform of cloaks cut into the shape of dragon wings and masks in the shape of dragon horns.

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
The ranks, if any, within the Cult are unknown. It is known that they require a period as an initiate before becoming a full member of the group.