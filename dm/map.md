# Creating a map
The major reason for creating a map is to know where things generally are. Further, a DM may want to know how long does it take to travel from one place to another. There are two approaches I like to this problem: hexcrawl and pointcrawl.

## Pointcrawl
A pointcrawl is used when you want to know how far apart are two important places. Note that the world of Samzarim allows for vertical and horizontal travel. There is no reason why players couldn't use a skyship and travel to their destination in a direct line. If you used only a pointcrawl in a Samzarim campaign you would have to create a fully connected graph with travel time coresponding to the points place in the graph. Such endevour would be fruitless and miserable. Instead, use a hexcrawl for your overall map.

That being said, the pointcrawl has its place in a Samzarim campaign. There are several major uses. Travel routes between places when players don't have a skyship and need to catch a ride. A route which is faster than taking a skyship e.g. a train/skytrain. And lastly *using pointcrawl inside of a hexcrawl*. This approach can be employed when you really want to pack a lot of adventure into each hex. This approach is inspired by [Summer's End](https://questingblog.com/summers-end/). There is a lot of adventure you can cram into a single hex and it is nice to know how long travel takes in between places.

### How to generate a random pointcrawl
Take some dice and a paper. The size of the paper and the number of dice is variable, choose according to your needs and resources. Throw the dice onto the paper. Take note of the place where the dice landed and key them using numbers, letters etc. You now have a series of places on a map. You may use dice of size according to your random tables. Generally tables in Samzarim are d20s. Either use the number rolled on the dice which landed in the corresponding place or pick a place and generate separately. Connect the places either before or after they are generated. To connect, make 1-4 connections with other places in the graph. You may connect the closest places or you may choose them randomly by rolling dice. If the number of places on the graph doesn't correspond to some nice dX number, you may use modulo e.g. number of places is 7 and you want to use a d20, place 1 gets chosen when 1, 8, 15 is rolled. You should end up with a keyed graph. Now you need to evaluate the travel time. Use 1-3 d6 to determine the travel time depending on how long the connection is. The travel time may be in days, hours etc. depending on the meaning of the pointcrawl. Pointcrawl inside of a hexcrawl should use hours.

Now you have an evaluated graph which you can use to determine the travel time. You may generate the meaning of the connections. Remember, portals may be used to connect far away places with arbitrary travel time (time shift or instant).

This method was taken from [Vaults of Vaarn](https://vaarn.github.io/)

## Hexcrawl
A hexcrawl takes place on a map divided into hexagons. This form of a map is ideal for random exploration when the players decide to into some direction. Hexcrawl can be used to determine the *rough distance* traveled when two places are not directly connected by a road. For example, the party decides to take a "shortcut" through the wilderness and now the DM needs to determine if it is a shortcut. Hexcrawl is ideal for Samzarim campaign as the maps consist of floating islands. Unfortunately, Samzarim uses *verticality*. This means if you are a perfectionist and need the know how many days of travel you need to add for changing latitude, you will need 2 maps, one horizontal - a classic map, and one vertical - a map showing the latitudes of the islands. Otherwise use a *1d20* to determine the latitude of an island, for each change in latitude during travel, add *1/5 of day traveled*.

Hexcrawls are frontloaded adventures, meaning you will have to do a lot of work in the beginning but the rest of the campaign should go smoothly. The DM Hexcrawl map should not be decorated or drawn - note down only important information, especially hex keys, you may make notes in hexes for faster lookup (icons for example). If the players are given a map, it should give a *very rough* idea where things are. It should only denote where things generally are and the very general movement of the islands. You may use a horizontal map with latitudes of islands noted next to them and curves or arrows to denote the travel of the islands. The player don't have to know about all of the islands, they only need to know of the major ones e.g. major story islands. In exploration mode, let the players map themselves.

Each hex should be about 10 miles/16 km. Note that, despite this being fantasy, in real life you can hardly find a 16 km radius, where there is not a single place of interest. A place of interest may even be a natural wonder or a place with a nice view - it doesn't have to be a ruin, dungeon, monster. The goal of a hexcrawl is twofold. First, so the DM can determine rough distance. Second, to make exploration wonderful. In a normal hexcrawl, it shouldn't happen that a hex is blank and there is nothing to explore. In a Samzarim hexcrawl, there may be blank hexes as they denote large distances between islands. Note that some islands may move in Samzarim. A hexcrawl is also good for this as you can easily determine how fast the island is moving and the trajectory of its movement.

### How to create a hexcrawl
First we will fill the hexcrawl map:
* key the hexes - so you can identify the hex - I advise numbers (roman perhaps, for flavour) 
* choose a hex
* determine the number of islands in the hex and their sizes - table below
    * key separate islands - using letters
        * now each island is identified by the hex number and its letter
* assign a *1d6 + 2* score to the hex
    * note that size of an island has effect on the amount of possible content on it
* determine the cost of a place using *1d4*
    * substract the cost from the score
    * roll on a random table according to the cost to generate a place
* you may print a single hex template for each hex
    * make a pointcrawl out of the hex
* you may determine the movement of the islands (separately for each or as a cluster)
    * identify the island
    * choose movement according to table below
    * choose a random hex and latitude
        * some islands may travel away from the map only to return later
        * rolling max number twice - choose two end points randomly (hex and latitude)
    * draw a curve to denote travel
        * for exit draw a curve between the end points and the original position of the island (hex)

Use the table bellow to clear up any questions about the number and size of arbitrary islands.
<table><thead>
  <tr><th>Roll</th><th>Number of islands</th><th>Island size</th><th>Max points</th><th>Size intuition</th></tr></thead>
<tbody>
  <tr><td>1</td><td>1d6</td><td>miniscule</td><td>1</td><td>enough for a small shrine, tree, hut, clearing</td></tr>
  <tr><td>2</td><td>1d20</td><td rowspan="2">small</td><td rowspan="2">2</td><td rowspan="2">enough for a house and a lighthouse</td></tr>
  <tr><td>3</td><td>1d20</td></tr>
  <tr><td>4</td><td>2d12</td><td rowspan="2">medium</td><td rowspan="2">3</td><td rowspan="2">quarter of a hex or less</td></tr>
  <tr><td>5</td><td>3d12</td></tr>
  <tr><td>6</td><td>2d20</td><td rowspan="2">big</td><td rowspan="2">5</td><td rowspan="2">up to half a hex</td></tr>
  <tr><td>7</td><td>10d10</td></tr>
  <tr><td>8</td><td>1d100</td><td rowspan="2">large</td><td rowspan="2">8</td><td rowspan="2">more than half the hex</td></tr>
  <tr><td>9</td><td>2d100</td></tr>
  <tr><td>10</td><td>5d100</td><td rowspan="2">hex sized</td><td rowspan="2">13</td><td rowspan="2">enough for a megadungeon</td></tr>
  <tr><td>11</td><td>10d100</td></tr>
  <tr><td>12</td><td>island belt (meteors)</td><td>gargantuan</td><td>21</td><td>also vertically large</td></tr>
</tbody></table>

Feel free to use a gargantuan island for a mega dungeon. A mega dungeon may appear on a miniscule island in the form of a portal to the dungeon. The island sizes are referential.

This approach should be doable for a Samzarim game as more than half the hexes will be blank

## Filling the map
### Locations
| Roll | Small               | Medium              | Large                 | Gargantuan      | But...      | Location     | Environment |
|------|---------------------|---------------------|-----------------------|-----------------|-------------|--------------|-------------|
| 1    | Ruins               | Ruins               | Ruins                 | City ruins      | Cursed      | Waterfall    | Mountainous |
| 2    | Grave               | Graveyard           | Sepulchre             | Catacombs       | Undead      | River bank   | Hills       |
| 3    | Camp                | Clan camp           | Warcamp               |                 | Infested    | Flower field | Forest      |
| 4    | Hut                 | Homestead           | Farm                  | Elysium         | Relaxing    | Underground  | Plains      |
| 5    | View                | Oasis               | Natural wonder        | Natural wonder  | Dangerous   | Overgrowth   | Mangrove    |
| 6    | Fight aftermath     | Battlefield         | Massacre              | Necropolis      | Beautiful   | Flying       | Swamp       |
| 7    | Den                 | Lair                | Grazing fields        | Wasteland       | Treacherous | Delta        | Rainforest  |
| 8    | Shrine              | Sanctuary           | Mystic Labyrinth      | World secret    | Mystical    | Lake         | Delta       |
| 9    | Waypoint            | Monastery           | Temple                | Sabbath         | Magical     | Pools        | Vale        |
| 10   | Tower               | Castle              | Fortress              | Bastion         | Angelic     | Geyser       | Highlands   |
| 11   | Anomaly             | Anomaly             | Anomaly               | Anomaly         | Demonic     | Grove        | Plateau     |
| 12   | Altar               | Dungeon             | Dungeon               | Dungeon         | Djinni      | Coast        | Canyons     |
| 13   | Shipwreck           | Shipwreck/s         | Ship graveyard        | Shipfall        | Ritual      | Plain        | Monoliths   |
| 14   | Cave                | Caverns             | Cave system           | Underdark       | Bloody      | Hilltop      | Lakes       |
| 15   | Ancient device      | Ancient device      | Ancient device        | Ancient device  | Witch       | Oasis        | Wasteland   |
| 16   | Tree                | Grove               | Starfall              | Palace          | Wealth      | Valley       | A mountain  |
| 17   | Monolith            | [Mines](#mines)     | [Balzac mines](#mines)| Undercity       | Secret      | Creek        | Wetland     |
| 18   | Nest                | Vault               | Vault/s               | Vault/s         | Vampiric    | Cliff        | Tundra      |
| 19   | Elemental formation | Elemental form.     | Elemental form.       | Elemental form. | Monstrous   | Underwater   | Flying rocks|
| 20   | Roll twice, combine | Roll twice, combine | Roll twice, combine   | Roll twice, combine | Roll twice, combine | Roll twice, combine | Roll twice, combine |

### Ruins

### City

### Camp

### Farm

### Graveyard

### Catacombs

### Grave

### Ancient device

### Strange Stone

### Lair

### Nest

### Vault

### Dungeon

### Prison

### Cave/s

### Anomaly

### Castle/Bastion

### Shipwreck

### Tree

### Tower

### Aftermath

### Religious place

### Starfall

### Sabbath


### Mines
Balzac mines include a town or even a city. You may also consult [this table](https://www.reddit.com/r/BehindTheTables/comments/43ufyr/mines/). In case of Balzac mines, roll twice on the table, except for form and use.

| Roll | Form | Risk | Also... | Use |
|------|------|------|---------|-----|
| 1    | Stone       | Collapsing       | Underwater         | Magical      |
| 2    | Crystal     | Gas              | Time anomaly       | Edible       |
| 3    | Bark        | Dug too deep     | Anomalous being    | Armor        |
| 4    | Bones       | Curse            | Abandoned wealth   | Decoration   |
| 5    | Oil         | Infested         | Artifact           | Religious    |
| 6    | Fungus      | Undead           | Secret             | Building     |
| 7    | Ethereal    | Cultists         | Vault              | Alchemy      |
| 8    | Flesh/blood | Monster          | Ritual             |              |
| 9    | Artifacts   | Bandits          | Goblin camp        |              |
| 10   | Scrap       | Agents           | Fungus infestation |              |
| 11   |             | Angelic/demonic  | Djinni             |              |
| 12   |             | Magical/mystical | Lair               | Mystical, roll again |
