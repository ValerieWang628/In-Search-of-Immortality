# [In-Search-of-Immortality](http://play2.textadventures.co.uk/Play.aspx?id=editor/94ebb875-d288-423a-afb6-44cacc98429d%2fIn+Search+of+Immortality.aslx)

## Game Overview:
[In Search of Immortality](http://play2.textadventures.co.uk/Play.aspx?id=editor/94ebb875-d288-423a-afb6-44cacc98429d%2fIn+Search+of+Immortality.aslx), is a [text adventure game](https://en.wikipedia.org/wiki/Text-based_game), also known as an interactive fiction. 
This program is written in a language called [Quest](http://textadventures.co.uk/quest), a free and open programming platform specifically for text adventure games.
By interacting with the scripts I have designed, the player will manage to reach the final goal with the guidance of NPCs. 

This project was created as one of the assignments of the course Programming for Game Designers. The assignment randomly assigned students with 3 particular words/phrases that must be used in the game. For me, I was assigned with an object called bottled water, a verb called empower, and a place called the forest of ghosts. Thus, the three words was incorporated in my game design. Bottled water works as one of the important tools, 'empower' is one of the transformations and the names of other places were created to match the forest of ghosts.

👉🏼To play the online version of this game, please click: [In-Search-of-Immortality](http://play2.textadventures.co.uk/Play.aspx?id=editor/94ebb875-d288-423a-afb6-44cacc98429d%2fIn+Search+of+Immortality.aslx)

👉🏼See a snapshot of the online version: (click the screenshots to jump to the original files)
<p align="center"> 
<img src="https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/snap/OnlineVersionSnap.png" width= "500" height = "367">
</p>

## Game Plot Synopsis:
In this game, you as the player will launch a quest for the Amethyst of Immortality. 
During your adventure, there will be dangerous traps and enemies to annihilate you while there will also be NPCs to guide you through it.


##### Welcome Prompt for the Player:
>*Welcome, brave explorer.*
*You as the most qualified adventurer, have been selected to complete the journey of seeking immortality. The ultimate reward for you is the Amethyst of Immortality. If you manage to fetch it and keep it safe, you will protect yourself from any kind of demise. 
However, this journey will be extraordinarily dangerous. 
All these unfamiliar places can send you to the reaper easily. 
There are disgusting creatures and fatal mechanisms waiting to annihilate you.
But, there are also wise people hidden in the corners to guide you through all the difficulties. 
If you are willing to ask, they will tell you what you need to know.*
*Be ready and careful, young traveler!*

## Game Location List:
There will be 4 main places in this game. 
They are:
<pre>
The Swamp of Ant Soldiers

The Forest of Ghosts

The Ocean of Finman

The Castle of Dwarf
</pre>

Meanwhile, there are two sub-rooms in the Castle of Dwarf. They are:

<pre>
The Mirror Ballroom

The Throne Hall
</pre>

In the online playable version, on the top of the web page, there will be a real-time map for the player to refer to. 
If the player moves him/herself to a specific room, the map will change according to the player's movement.
This will better help the player to understand the game.

👉🏼Snapshot of the map: (click the screenshots to jump to the original files)
<p align="center"> 
<img src="https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/snap/map.png" width= "500" height = "479">
</p>

## Game Design Documents:
### Main Document:
This game is designed via a [game dependency chart](https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/Game%20Dependency%20Flow%20Chart%20for%20In%20Search%20of%20Immortality.pdf). (See what is a [game dependency chart](https://grumpygamer.com/puzzle_dependency_charts))

This dependency chat is the main design document for this game.
It turns out to be very similar to the project management chart I made before.
(No wonder! Every game is a project that is made up of multiple smaller projects.)
Thus, the chart also includes concepts like critical path and alternative path.
Similar to project management, when designing the dependency chart, I worked in a backwards order where I set the final goal of the game first, then the second last step before final achievement, and before. 
This is to make sure the dependency relations and critical paths are all right. When implementing the game with the dependency chart as a reference, I workd in a forward order.

😧Please note: This dependency chart is the ultimate spoiler! If you would like to enjoy the puzzles, please do not look at this design document because it is how I assembled all the plots and traps.

👉🏼Snippet of the dependency chart: (click the screenshots to jump to the original files)
<p align="center"> 
<img src="https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/snap/dependency.png" width= "400" height = "552">
</p>

### Two supplemental Document:
Along with the game dependency chart, there are two additional documents for supplemental illustration:

1. [Location Map](https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/Detailed%20Location%20Map%20Illustration%20for%20Game.pdf) : This map helps designers to understand the relative positions of the rooms -- which one is to the east/west/north/south of which room, etc.

👉🏼Snap shot of the location map: (click the screenshots to jump to the original files)
<p align="center"> 
<img src="https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/snap/key.png" width= "400" height = "187">
</p>

2. [Legend and Annotation](https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/legend%20and%20Annotation%20for%20Game%20Chart.pdf): This illustration helps designers to understand the nodes with different shapes in the dependency chart -- which path is critical/alternative; which node represents death/victory, etc.

👉🏼Snap shot of the annotation: (click the screenshots to jump to the original files)
<p align="center"> 
<img src="https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/snap/annotate.png" width= "400" height = "187">
</p>

### Playtest Report During Interim Implementation:
Finally, there is a preliminary [playtest report](https://github.com/ValerieWang628/In-Search-of-Immortality/blob/master/Playtest%20Report.txt) of the game. It records several critical checkpoints of the player's difficulty in this game. 
Based on the listed difficulties, there are implementation plans for improvement so that bugs and design flaws can be fixed. 

This game also playtested for many times. 
The playtesters range from newbies who barely plays any kinds of games to professional AAA fervants.
Thus, the play time ranges from infinity(meaning that the player can never make it to the end) to 30 mins.

## Note for game interaction:
As some players have no previous experience with text adventure, it might be hard for them to understand the mechanism of the interaction.
For example, they might not know the tricks of asking an NPC to for clues or objects. 
Since text adventure games are strongly riddle-based games, almost every clue is critical. Missing one clue might cause an unexitable quagmire.

## Other Links:
[Scripting documentation of Quest](http://docs.textadventures.co.uk/quest/scripts/)

