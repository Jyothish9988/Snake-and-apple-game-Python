# Snake and apple game Python
 Snake and apple game using python
 <img src="images/1.png"    >
<h2>Dependencies</h2>
<p>1.pygame

pip install pygame</p>

<h2>Descriptions</h2>
<p> This is a basic implementation of the classic Snake game using the Pygame library. It begins by initializing the necessary libraries, including Pygame for game development, time for handling time-related functions, and random for generating random numbers. The script then defines color constants using RGB values. The game window is set up with specific dimensions, and a clock object is created to control the game's speed.

The characteristics of the snake and apple are configured, specifying the size of each snake segment (snake_block) and the speed of the snake (snake_speed). Additionally, fonts are set for displaying text in the game. Two functions are defined to handle the display of the player's score and the drawing of the snake on the game window.

The main game loop (gameLoop()) orchestrates the entire gameplay. It initializes variables such as the snake's initial position, movement changes, and the initial length of the snake. The position of the food (apple) is randomly set. The loop continues until the game is over, with conditions for the snake hitting the window boundaries or colliding with itself. If the player loses, a message is displayed, allowing them to choose to play again or quit the game.

User input is captured to control the snake's movement (left, right, up, down). The game continuously updates the display, checks for collisions, and handles the spawning of new food. The clock regulates the game speed. Once the game is over, the Pygame environment is properly quit. </p>