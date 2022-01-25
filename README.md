# App21-06: Zuul Game - Console Application
*[IntelliJ Ultimate IDEA IJ-App06-Zuul Project](https://github.com/BNU-CO452/BlueJ-Apps)*

## Description (10 Marks)

Welcome to Dungeon Slayer where you will go from Rags to Riches. Welcome to the Kingdom of Inverness. You find yourself in the Kingdom of Aavak, the infamous kingdom known for its thievery and mischievousness. It is there that you hear of “the legend of the Phoenix ''. The legend where the former King of Aavak went on a conquest to defeat the majestic fiery Phoenix. After months of waiting, Aavak's king never returned and was presumed deceased. A struggle for the throne began and after months of fighting, murder and mischief. The High King of Inverness traveled to the town of Aavak. After his arrival he concluded to the townspeople of Aavak, that whoever was willing to fight the Phoenix and return the crown of Aavak, was promised the City of Aavak and the princesses hand in marriage. 

This is where your journey starts, a race to wealth and riches.


The game can be won by defeating all enemies you encounter as well as collecting the iterms. In contrast, the game can be lost by being killed against your enemies, failing to defeat the final boss and failing to collect the majority of the items. 


This game is based on the classic console based game  *Colossal Cave Adventure* by Will Crowther (1975) see
  
* [Colossal Cave Adventure Short Play](https://www.youtube.com/watch?v=sfGrPM5Bxeo&ab_channel=FridayNightArcade)     
* [Colossal Cave Adventure Play Through](https://www.youtube.com/watch?v=O3etkSoHrR8&ab_channel=GladeSwope)      
* [Colossal Cave Adventure Clone GitHub Repo](https://www.youtube.com/watch?v=UFu1WGJP6rQ&ab_channel=RedHatDeveloper)  
* [GitHub Repository](https://github.com/tvall43/open-adventure)   
* [Play the Game](https://grack.com/demos/adventure/)

## User Requirements (10 Marks)
*The student should replace the general user requirements below with a full set of specific user requirements of their chosen game* 

Player objects with health and energy and a score.
Items that can be picked up - Helmet, Shield, Boot, Chest Plate etc.
Map - displays 25 locations and can be used as a guide.

Commands:
You slash at the “” and do “” amount of damage.

You have suffered”” amount of damage.

You drink a potion and heal “”.

You stab at the “” and do “” amount of damage.

BASIC commands: directional commands, combat commands, inventory check.

Objective: 

WIN - kill all enemies and defeat the final boss whilst collecting all items. 

LOSE - fail to kill all enemies and the final boss, fail to collect all the items and die from health damage.



## Zuul Locations (10 Marks)
*The student should replace this simple diagram to show how all the locations in the new game connect*
![Zuul Starting Locations](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Zuul-00.jpg)

## Software Design (20 Marks)

### UML Use Case Diagram (20 Marks for 10 use cases)
*The student should add a use case diagram summarising the functionality of the game.  
This can be reversed engineered or created from scratch before coding is completed.* 

![Use Case Diagram](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/App06%20Use%20Cases.jpg)  

### UML Class Diagram (20 marks for 10 classes)
*The student should replace this class diagram with a full class diagram of their completed game showing attributes and methods* 

The design must be an extension of this basic design which is based on the [Command Design Pattern](https://refactoring.guru/design-patterns/command).
Using this pattern each **Command** is a kind of **ZuulCommand** (inheritance) and is responsible for executing that command.

![Basic Design](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/App21-06%20Classes.jpg)

*The student should include a more detailed Class Diagram *

## Black Box Testing (20 marks for 20 Black Box Tests)
*Each member of the team must product at least 10 Black Box tests and a minimum of 20 in total*
| Test No | Proposed Test | Data Entered | Expected Result | Actual Result | Comments |
|:---:|-----|------|------|------|------|    
| 01 | South from Valley  | "Go South" from valley | Enter Slit |  | |    
| 02 | West from Valley | "Go West" from valley | No exit message |  | |    
| 03 | Wrong Direction | "Go Home" from valley | Go where? message |  | |    
## Game Walkthroughs (Testing 40% of total)

*To test the game the student must produce one example walkthrough of playing the game such as the one shown below, and demonstrate a walkthrough live.
These walkthroughs should include*

1. Going into each of the rooms
2. Winning the game
3. Loosing the game
4. Picking up each item
5. Using each item
6. Using each command word
7. Updating the player status and score
   
![Example Game](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Zuul-01.jpg)

## Programming Issues (20 marks for 10 issues)
*Each member of the team must have posted at least 5 issues and a total of 10 issues*

## Application Evaluation (10 Marks for 5 improvements)
*An evaluation with list of at least 5 ways the game can be improved or extended.*
