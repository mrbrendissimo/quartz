---
tags:
  - Category/Region
obsidianUIMode: preview
MyContainer:
mapCalc1: NaN
map_width_x: 4375
map_height_y: 2773
---
> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`

> [!NOTE] Parent Planet: `INPUT[suggester(optionQuery(#Category/World)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet  
>> id: wm_Savage-Frontier ### Must be unique with no spaces  
>> image: [[wm_Savage-Frontier.webp]] ### Link to the map image file. Do not add a ! in front of the image  
>> bounds: [[0,0], [2773, 4375]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
>> height: 500px ### Size of the leaflet embed in px on your screen  
>> width: 95% ### Size of the leaflet embed in your note  
>> lat: 1386.5   ### To center the map, make this half of the map height.  
>> long: 2187.5 ### To center the map, make this half of the map width.  
>> minZoom: -2.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
>> maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
>> defaultZoom: -2.0 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
>> zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
>> unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
>> scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
>> recenter: false  
>> darkmode: false ### marker
>
>> [!note|no-title] Town Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General Info),
>> option(2, 🌐Region Details),
>> option(3, 📝GM Notes),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General Info|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Region Details|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🏡Hubs),
> option(2, 🍎Points of Interest),
> option(3, ⚔️Groups),
> option(4, 💭Quests),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Hubs|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Points of Interest|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Groups|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Quests|no-h clean]]

---
# General Info

The Savage Frontier (also known as the North) is a cold, rugged, sparsely populated land of snow-capped mountains, rocky hills, sprawling forests, and foggy vales. Isolated strongholds, ancient burial mounds, and the ruins of many forgotten empires dot this vast landscape. Bounded by the Sea of Swords to the west and the desert of Anauroch to the east, the Savage Frontier extends as far north as Icewind Dale and as far south as the town of [[Daggerford]]. Old roads stretch across this great expanse, linking the dwarven strongholds and mines in the mountains to the coastal settlements, frontier towns, and fortified outposts of humans and other folk. These roads are long, lonely, or poorly defended, making them dangerous to traverse. In fertile valleys, towns and cities have sprung up, separated by dozens if not hundreds of miles of untamed wilderness haunted by bandits, barbarians, and monsters.

Evil dragons stirred into action by their dark queen, Tiamat, threatened the settlements of the Savage Frontier for a time. Ultimately, they were defeated and forced to withdraw to their lairs, while Tiamat was banished to the Nine Hells. Fear of the dragons’ wrath has faded quickly with the coming of a new threat: giants. The peoples of the North are no strangers to giant incursions. Frost giants have long claimed the Spine of the World as their demesne, and hill giants are known to scrounge for food in the untamed hills. But now, in the past couple of months, giants of every kind have emerged from their strongholds in force to threaten civilization as never before — and not just frost giants and hill giants, but also stone giants, fire giants, and cloud giants. All of the giants are in an uproar. Reports of giant attacks throughout the North have reached the coastal cities of Luskan, Neverwinter, and [[Waterdeep]], stoking fears that the giants are waging war against humans, dwarves, elves, and other small folk.

# Region Details

**Dominant Races:**  
**Climate:** 
**Seasons:**

# GM Notes

Make notes of what you need to track in the region here. 

# Hubs

`BUTTON[button_hub]` **Hubs** Places where people live - Cities, Towns, Villages, Hamlets, Encampment, Keeps, Fortresses, Strongholds.

```dataview
TABLE WITHOUT ID link(file.name) AS "Hubs(s)", MyCategory as "Type"
FROM "2-World/Hubs"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

# Points of Interest

`BUTTON[button_pointofinterest]`  Places that can be explored. 

```dataview
TABLE WITHOUT ID link(file.name) AS "Points of Interest(s)", MyCategory as "Type"
FROM "2-World/Points of Interest"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

# Groups

`BUTTON[button_group]` Groups of people and power - religious, cults, guilds, military

```dataview
TABLE WITHOUT ID link(file.name) AS "Group(s)", MyCategory as "Type"
FROM "2-World/Groups"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```


# Quests

`BUTTON[button_quest]` **P - Philosophy** (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums

```dataview
TABLE WITHOUT ID link(file.name) AS "Quest(s)", questGiver AS "Quest Giver", questStatus AS "Status"
FROM "2-World/Quests"
WHERE contains(MyContainer, this.file.link)
SORT file.name ASC
```

