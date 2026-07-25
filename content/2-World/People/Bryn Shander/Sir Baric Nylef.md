---
MyContainer:
  - "[[2-World/Hubs/Bryn Shander.md|Bryn Shander]]"
  - "[[B8. Kelvin’s Comfort|B8. Kelvin’s Comfort]]"
MyCategory:
tags:
  - Category/People
obsidianUIMode: preview
aliases:
  - characters other name
NoteStatus: ❓
char_status: Alive
char_race: Human
char_gender: Male
char_items:
char_age: Adult
parents:
  - Josh
  - Susan
children:
  - Bob
  - Fred
enemies:
  - Zander
allies:
  - Emyerson
  - Bob
  - Frank
siblings:
  - Flip
partner:
  - Jane
Connected_Quests:
  - "[[Attack on Bryn Shander|Attack on Bryn Shander]]"
  - "[[Sir Baric Nylef’s Quest|Sir Baric Nylef’s Quest]]"
Connected_Groups:
  - "[[Order of the Gauntlet|Order of the Gauntlet]]"
---




> [!NOTE|div-m] Parent Location: `INPUT[inlineListSuggester(optionQuery(#Category/Hub),optionQuery(#Category/Region),optionQuery(#Category/Place),optionQuery(#Category/PointofInterest)):MyContainer]`

> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[sir-baric-nylef.webp|300]]
>
>> [!div-m|no-title] Place Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 📒Statblock),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#Statblock|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, ⚔️Inventory),
> option(2, 🔗Connections),
> option(3, 🧑‍🤝‍🧑Relationships),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Inventory|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Connections|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Relationships|no-h clean]]

---

# General

Name: `= this.file.name`

Status: `INPUT[inlineSelect(option(Alive), option(Dead)):char_status]`

Race/Species: `INPUT[template-Race][:char_race]`

%% The options in the drop-down above are controlled via the Meta Bind Input Field Templates in the Settings %%

Gender: `INPUT[inlineSelect(option(Male), option(Female), option(Other)):char_gender]` 

Age: `INPUT[inlineSelect(option(Infant), option(Child), option(Teenager), option(Young Adult), option(Adult), option(Elder)):char_age]`

---

_**Ideal:**_ “Evil must not be allowed to thrive in this world.”

_**Bond:**_ “Tyr is my lord; the order, my family. Through my actions, I shall honor both.”

_**Flaw:**_ “I’m not afraid to die. When Tyr finally calls me, I’ll go to him happily.”

# Statblock

```statblock
monster: Sir Baric Nylef (SKT)
```

# GM Notes

One of the patrons of [[B8. Kelvin’s Comfort|Kelvin's Comfort]] is Sir Baric Nylef, a knight of Tyr and a member of the [[Order of the Gauntlet]]. He’s hoping that a few shots of Flamebeard’s Firebrandy will keep a nasty cold at bay while he keeps an eye out for a dwarf named Worvil “the Weevil” Forkbeard, a criminal rumored to be hiding in Ten-Towns. The Weevil led a gang of dwarf brigands that raided summer caravans traveling between [[Luskan]] and Mirabar. He also spearheaded several raids on the Mines of Mirabar, stealing food and drink mainly. The Order of the Gauntlet captured most of his gang, but Worvil disappeared into the mountains. Interrogation of the captives led Baric to discover the Weevil’s craving for Flamebeard’s Firebrandy. So, Baric has adopted the guise of an unemployed caravan guard, and his plan is to hang around Kelvin’s Comfort for a few days, on the chance that his quarry will walk right through the door.

# Inventory

The following items belong to `= this.file.name`.

```dataviewjs
// 1. grab all pages in the folder
let pages = dv.pages('"3-Mechanics/Items"').values;

// 2. shuffle (Fisher–Yates)
for (let i = pages.length - 1; i > 0; i--) {
  const j = Math.floor(Math.random() * (i + 1));
  [pages[i], pages[j]] = [pages[j], pages[i]];
}

// 3. take the first two
let pick = pages.slice(0, 1);

// 4. render table of clickable links + Gender
dv.table(
  ["Random Item", "cost", "weight"],
  pick.map(p => [
    dv.fileLink(p.file.path),        // clickable note link
    p.cost ?? "—",                  // frontmatter field (falls back to “—” if missing)
    p.weight ?? "—"                  // frontmatter field (falls back to “—” if missing)
  ])
);
```

# Connections
Is the person linked to any groups or quests?

Quests: `INPUT[inlineListSuggester(optionQuery(#Category/Quest)):Connected_Quests]`

Groups: `INPUT[inlineListSuggester(optionQuery(#Category/Group)):Connected_Groups]`

# Relationships

List important relationships here. 

```dataviewjs
var parents = dv.current().parents ?? [];
var children = dv.current().children ?? [];
var enemies = dv.current().enemies ?? [];
var allies = dv.current().allies ?? [];
var siblings = dv.current().siblings ?? [];
var current = dv.current().file.name;
var partner = dv.current().partner ?? [];

dv.paragraph("```mermaid\nflowchart LR\n" +
  // Parents with internal-link on individual nodes only
  (parents.length > 0 ? parents.map((parent, index) => `P${index + 1}[${parent}]:::internal-link\nP${index + 1} --> Current\n`).join('') : '') +
  
  // Current node
  `Current[${current}]\n` +
  
  // Partner group node (no internal-link applied)
  (partner.length > 0 ? `PT[Partner]\nCurrent --> PT\n` : '') +
  
  // Individual partners with internal-link
  (partner.length > 0 ? partner.map((p, index) => `PT${index + 1}[${p}]:::internal-link\nPT --> PT${index + 1}\n`).join('') : '') +

  // Children group node (no internal-link applied)
  (children.length > 0 ? `C[Children]\nCurrent --> C\n${children.map((child, index) => `C${index + 1}[${child}]:::internal-link\nC --> C${index + 1}\n`).join('')}` : '') +

  // Siblings group node (no internal-link applied)
  (siblings.length > 0 ? `S[Siblings]\nCurrent --> S\n${siblings.map((sibling, index) => `S${index + 1}[${sibling}]:::internal-link\nS --> S${index + 1}\n`).join('')}` : '') +

  // Enemies group node (no internal-link applied)
  (enemies.length > 0 ? `E[Enemies]\nCurrent --> E\n${enemies.map((enemy, index) => `E${index + 1}[${enemy}]:::internal-link\nE --> E${index + 1}\n`).join('')}` : '') +

  // Allies group node (no internal-link applied)
  (allies.length > 0 ? `A[Allies]\nCurrent --> A\n${allies.map((ally, index) => `A${index + 1}[${ally}]:::internal-link\nA --> A${index + 1}\n`).join('')}` : '') +

  // Styling: Apply internal-link only to individual nodes, not group nodes
  `class ${parents.length > 0 ? parents.map((_, index) => `P${index + 1},`).join('') : ''}Current${children.length > 0 ? children.map((_, index) => `C${index + 1},`).join('') : ''}${siblings.length > 0 ? siblings.map((_, index) => `S${index + 1},`).join('') : ''}${enemies.length > 0 ? enemies.map((_, index) => `E${index + 1},`).join('') : ''}${allies.length > 0 ? allies.map((_, index) => `A${index + 1},`).join('') : ''} internal-link;`
)
```

> [!NOTE]- Relationship Config - Enter name of People Notes
> `BUTTON[button_person]` Nodes will link to notes of the same name. 
> 
> | Parents    | Partner    | Children |
> | --- | --- | --- |
> | `INPUT[list:parents]`    | `INPUT[list:partner]`    | `INPUT[list:children]`  |
> 
> | Siblings    | Enemies    | Allies |
> | --- | --- | --- |
> | `INPUT[list:siblings]`    | `INPUT[list:enemies]`    | `INPUT[list:allies]`  |



