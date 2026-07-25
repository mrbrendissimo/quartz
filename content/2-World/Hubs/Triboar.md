---
tags:
  - Category/Hub
container: Test
MyContainer: "[[2-World/Regions/Savage Frontier.md|Savage Frontier]]"
MyCategory: Town +200
obsidianUIMode: preview
mapCalc1: NaN
---

> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`


> [!NOTE|div-m] Parent Region: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet  
>> id: tm_triboar ### Must be unique with no spaces  
>> image: [[tm_triboar.png]] ### Link to the map image file. Do not add a ! in front of the image  
>> bounds: [[0,0], [5000, 4025]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
>> height: 500px ### Size of the leaflet embed in px on your screen  
>> width: 95% ### Size of the leaflet embed in your note  
>> lat: 2500 ### To center the map, make this half of the map height.  
>> long: 2012.5 ### To center the map, make this half of the map width.  
>> minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
>> maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
>> defaultZoom: -3 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
>> zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
>> unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
>> scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
>> recenter: false  
>> darkmode: false ### marker
>> ```
>
>> [!note|no-title] Town Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 🏃‍♂️‍➡️NPCs),
>> option(3, 📝GM Notes),
>> option(4, 🐎Travel),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#NPCs|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#Travel|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🛒Commerce),
> option(2, 🍎Agriculture),
> option(3, ⚔️Military),
> option(4, 💭Philosophy),
> option(5, ⚙️Industrial),
> option(6, 🏠Nesting),
> option(7, 👑Government),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Commerce|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Agriculture|no-h2 clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Military|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Philosophy|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Industrial|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Nesting|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Government|no-h clean]]

---
# General

Select Settlement: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

Select Category: `INPUT[inlineSelect(option(City +1500), option(Town +200), option(Village +80), option(Hamlet <80), option(Encampment), option(Keep), option(Fortress), option(Stronghold)):MyCategory]`

The bustling mercantile town of Triboar stands where the [[Long Road]] meets the [[Evermoor Way]]. Triboar’s name is thought to have come from a traveler’s tale of slaying three boars here in the same day, over four hundred winters ago. The town is built on flat, fertile land, with a few natural rises here and there. Nearly half of Triboar’s population lives outside the town proper, on sprawling ranches and neighboring farmsteads, most of which lie to the north or east.

The current lord protector of Triboar is a good-natured Harper and ex-adventurer named [Darathra Shendrel](https://www.dndbeyond.com/monsters/27597-darathra-shendrel). Darathra enacts and modifies local laws (known as “the Lord’s Decree”), which are then enforced by the Twelve — a squad of a dozen mounted warriors drawn from the militia.

Triboar is a market for the horses raised by nearby ranches. Blacksmiths, harness-makers, and wagonworks also flourish in town. In addition, a number of guides operate out of Triboar. They take merchants and other travelers all over the Sword Coast, typically for stiff fees.

# NPCs

`BUTTON[button_person]` List important NPCs here. 

```dataviewjs
// 1) Hub’s vault-relative path
const hubPath = dv.current().file.path;

// 2) Helper to extract the path from a "[[path|alias]]" entry
function extractPaths(mc) {
  if (!mc) return [];
  const arr = Array.isArray(mc) ? mc : [mc];
  return arr
    .map(link => {
      const m = String(link).match(/\[\[(.*?)\|/);
      return m ? m[1] : null;
    })
    .filter(Boolean);
}

// 3) Find all Places whose MyContainer points to this Hub
const placePages = dv.pages(`"2-World/Places"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;
// collect their **paths**
const placePaths = placePages.map(p => p.file.path);

// 4a) Indirect People: whose MyContainer links to any of those placePaths
const indirect = dv.pages(`"2-World/People"`)
  .where(p => {
    const paths = extractPaths(p.MyContainer);
    return paths.some(path => placePaths.includes(path));
  })
  .values;

// 4b) Direct People: whose MyContainer links **directly** to this Hub
const direct = dv.pages(`"2-World/People"`)
  .where(p => extractPaths(p.MyContainer).includes(hubPath))
  .values;

// 5) Merge & dedupe by file path
const allPeople = [...indirect, ...direct];
const unique = Array.from(
  new Map(allPeople.map(p => [p.file.path, p])).values()
);

// 6) Build rows (Name clickable, Race, Gender, Associated Group)
const rows = unique.map(p => {
  const linkEl = dv.el("a", p.file.name, {
    href: "#",
    cls: "dataview-link",
  });
  linkEl.addEventListener("click", e => {
    e.preventDefault();
    app.workspace.openLinkText(p.file.path, dv.current().file.path);
  });

  const race = p.char_race ?? "";
  const gender = p.char_gender ?? "";
  let groups = p.Connected_Groups ?? [];
  if (!Array.isArray(groups)) groups = [groups];
  const assoc = groups.join(", ");

  return [linkEl, race, gender, assoc];
});

// 7) Render the table
dv.table(
  ["Name", "Race", "Gender", "Associated Group"],
  rows
);
```

# GM Notes

#### C. Cottage

Each of these plain stone cottages is home to 1d4 adult [commoners](https://www.dndbeyond.com/monsters/16829-commoner) and 1d4 - 1 children (noncombatants) of various ethnicities.

#### [](https://www.dndbeyond.com/sources/dnd/skt/rumblings#FFarm)F. Farm

Each of these plots of land contains a modest stone farmhouse, a wooden outhouse, and a tilled garden or pasture. The farm is occupied by 1d6 adult [commoners](https://www.dndbeyond.com/monsters/16829-commoner) and 1d6 - 1 children (noncombatants) of various ethnicities.

# Travel

%% For every other hub/location that you would like to see travel time to, add a line in the table and replicate the format provided. Change the Town name and link it to that towns note and then change the 88 in the formula to match the distance in miles to that place. Use a Leaflet map to measure the distance. %%

`VIEW[{Travel Calculator#HoursPerDay}][math]` hrs per day
[[Travel Calculator]]  / [[Exhaustion]] Level: `VIEW[{Travel Calculator#ExhaustionLevel}][math]`

| Destination |  Travel Days  |
| ---|---|
| [[Next Town A]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
| [[Next Town B ]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`

# CAMPING 

C - Commerce (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics
A - Agriculture (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants
M - Military (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports
P - Philosophy (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums
I - Industrial (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers
N - Nesting (Housing and Civil Engineering) - Residential Areas, Inns/Hotels
G - Government (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

## Commerce

This is the content

`BUTTON[button_place]` `BUTTON[button_person]` **C - Commerce** (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Commerce"
SORT file.name ASC
```

## Agriculture

`BUTTON[button_place]` `BUTTON[button_person]` **A - Agriculture** (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Agriculture"
SORT file.name ASC
```

## Military

`BUTTON[button_place]` `BUTTON[button_person]` **M - Military** (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Military"
SORT file.name ASC
```


## Philosophy

`BUTTON[button_place]` `BUTTON[button_person]` **P - Philosophy** (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Philosophy"
SORT file.name ASC
```

## Industrial

`BUTTON[button_place]` `BUTTON[button_person]` **I - Industrial** (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Industrial"
SORT file.name ASC
```

## Nesting

`BUTTON[button_place]` `BUTTON[button_person]` **N - Nesting** (Housing and Civil Engineering) - Residential Areas, Bridges, Parks, Inns/Hotels

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Nesting"
SORT file.name ASC
```

## Government

`BUTTON[button_place]` `BUTTON[button_person]` **G - Government** (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

```dataview
TABLE WITHOUT ID link(file.name) AS "Place(s)", MyCategory AS "Type"
FROM "2-World/Places"
WHERE contains(MyContainer, this.file.link)
  AND MyCategory = "Government"
SORT file.name ASC
```


