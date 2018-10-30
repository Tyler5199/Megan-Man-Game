#Demo Mega Man Project

##Project Description
This is a demo version of a knock off Mega Man game I created for my Game Development class. This is designed to play just like your typical Mega Man video game just on a smaller scale. 
There are only three levels in this version with the last level being a boss fight.  The objective of the game is to you’re your way through each level by navigate from platform to platform 
shooting enemies until you reach the boss battle. Once the boss is defeated you win the game a victory message is printed to the screen and the game exits.

##Installation
At the moment this game requires the last version of GameMaker Studio to operate. The current version of this software is GameMaker Sudio 2. A trial version of this program can be downloaded at yoyogames.com.

##How to Run 
To run the game open GameMaker Studio click the build button, and then click the run button. This will open up a second window that runs the game.

##Controls
Mega Man’s movement is all controlled by the directional keys. Press or hold the left or right key to move from left to right and press up key to jump. The Space bar fires projectiles and the 1,2, and 3 number keys
cycle through different suits which each fire different projectiles. Each type of projectile has a different fire rate and damage rate.

##Design
This game is designed to operate based off the collaboration of several different objects. For every item in the game an object is created for it(including text and sound).  Each level of the game is composed
of a different room object that is filled with other objects the player can interact with such as enemies and extra life tokens. Each object has a sprite and code designated to it. The sprite is just the visual
representation of the object and the code controls the actions of the object. For example, the player object uses several images of Mega Man in several different positions to capture his animations, and has code
written inside that adjust the players gravity, allows the player to move, interact with other objects, and play sounds when certain input is received from the keyboard. The main objects the player object interacts
with is the lives system and game over objects. These are two of the very few objects in the game without sprites. These are the only objects (besides the player) that remain constant from room too room. The lives system
object is created in room 0 and tracks the health and amount of lives the player object has. Once the player runs out of lives the game over object is created which displays a defeat message and restarts the game. The remaining
enemy, platform, gate, and life token objects all have their own assigned code and work together in each room object to allow the game to function. A slight adjustment to any code in any object could drastically affect the game.

#Development
This game was developed using GameMaker Studio 2 and is written in GameMaker Language.

#Acknowledgement
I would like to give special thanks to Dr. David Thornton for assisting me on this project.
