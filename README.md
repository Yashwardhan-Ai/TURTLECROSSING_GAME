**Turtle Crossing Game 🐢🚦**:
A fun and interactive Python game built using the Turtle Graphics library. The goal is to help the turtle safely cross the road while avoiding moving cars. As the game progresses, the cars move faster, making the challenge increasingly difficult.

**Features**
*Dynamic Gameplay: Cars spawn at random intervals and positions, moving across the screen.
*Level Progression: Successfully crossing the road increases the level, and car speed increases for added difficulty.
*Collision Detection: The game ends if the turtle collides with a car.
*Visual and Functional Feedback:
Level displayed on the screen.
"Game Over" message upon collision.

**Project Structure**
main.py: The main game loop managing interactions between the player, cars, and scoreboard.
player.py: Defines the player's movement and checks for crossing the finish line.
car_manager.py: Handles car creation, movement, and speed adjustments.
scoreboard.py: Manages level display and "Game Over" messages.

**How to Play**
Use the W key to move the turtle upward.
Avoid the cars as they move across the screen.
Cross the finish line at the top to level up and reset the turtle's position.
The game ends if the turtle collides with a car.
