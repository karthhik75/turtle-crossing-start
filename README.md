Turtle Crossing Game
A classic Turtle Crossing game developed using Python and the turtle graphics module. In this game, the player controls a turtle that tries to cross a busy road filled with cars. Each successful crossing increases the difficulty level by speeding up the cars. The game ends if the turtle collides with a car.

Table of Contents
Features
Installation
Usage
Files
Technologies Used
Contributing
License
Features
Player-controlled turtle that moves upwards to cross the road
Randomly generated cars that increase in speed as the level progresses
Scoreboard tracking the current level
"Game Over" screen when the player collides with a car


Usage
Use the Up arrow key to move the turtle forward.
Avoid the cars, and cross to the top of the screen to increase your level.
Each new level increases the speed of the cars, adding more difficulty.

main.py: Sets up the game environment and handles the main game loop.
player.py: Contains the Player class, which defines the turtle's behavior and movement.
car_manager.py: Contains the CarManager class, which creates and manages car movements and speed levels.
scoreboard.py: Contains the Scoreboard class, which displays the current level and shows "Game Over" when the player loses.

Technologies Used
Python: Programming language used for development.
Turtle Graphics: Used for graphical representation of the player and cars.
