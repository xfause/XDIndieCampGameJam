# The 2nd "Indie Camp Indie Camp - 48 Hours of Game Creation Challenge" Development Works

![](https://pic1.cdncl.net/user/xfause/common_pic/23868c410228abc80beae17f0fffd35a.jpg?imageView2/2/w/1280)

## Background and Theme

The development period is from December 7th to December 9th, 2018.

There are five members of the development team, two programmers, two artists, and one planner. I am in charge of the program and planning.

The theme of this game development is: Reborn.

## Design

To be honest, the theme of rebirth is already very common. The mechanism of dragging corpses and ordinary Roguelike dungeon games are very suitable for this theme. Therefore, at the beginning of the design, I decided to avoid these aspects in terms of theme and game mechanism.

Finally, the scope of rebirth is extended to the entire world and civilization, and the game mechanism is also transformed into a round card strategy game.

The background of the game is a world that has been over-exploited by human beings, and the ecology and the survival of human beings are in jeopardy. The map consists of hexagons. There are 3 types of buildings in the game. Each type has 3 levels, a total of 9 types of buildings, and a total of 10 types of units with open space. The 3 types of buildings are: natural buildings, waste land blocks, and factory buildings. The floor area of ​​buildings of different grades is 1 basic unit, 3 basic units, and 7 basic units.

Another mechanism in the game is the card system. There are also 9 types of cards in 3 types and 3 levels. They are Miracle Cards: you can turn wasteland blocks into open spaces, and Disaster Cards: you can turn natural buildings and factory buildings into Factory Buildings, Growth Cards: Turn blank plots into natural buildings. Each type of card is divided into 3 levels, and the cards of the corresponding level can only be used on the land of the corresponding level, that is, the level 2 miracle card can only be used on the level 2 wasteland. Each time five cards are randomly used by the player, the number of rounds of using a card is +1, and the player can choose to re-deal the card and the number of rounds is also +1.

Game mechanics revolve around two values: Prosperity and Faith. Each piece of land has its own initial prosperity value and faith value, so when entering each level, two values ​​are calculated according to the map. Each card will also have different effects on the two values. Miracle cards greatly increase Faith, Disaster cards greatly reduce Prosperity, increase Faith slightly, and Growth Cards increase Faith slightly. At the same time, the land that changes after using the card will also affect both values. The pass condition is to increase the Faith value higher than the target without making the Prosperity value lower than the target.

In order to make the game interesting and repeatable challenges, I originally wanted to add a record list that records the minimum number of rounds to clear, but it could not be completed due to time reasons.

Another major flaw is that because I am not very good at numerical planning, the numerical settings and numerical changes of many units are very simple linear changes, which can be improved here. In addition, the other areas that can be improved in the game are the cards. types and types of buildings.

## Screenshot

### Prototype

![](https://pic1.cdncl.net/user/xfause/common_pic/1046adc7c45375b1f672100313887e10.jpg?imageView2/2/w/1280)

### In-game screenshots

![](https://pic1.cdncl.net/user/xfause/common_pic/346a4843957a01bdf2ee8ec75dd9e759.jpg?imageView2/2/w/1280)

## Demo download

Game demo download:

Link: https://pan.baidu.com/s/14ZjtaHpOOVhaBr1dyfls9w Passwork: vued
