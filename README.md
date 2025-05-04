# Snake-Game
The Snake game is a simple arcade game where the player controls a snake that moves around to eat food. The goal is to keep eating food without crashing into the walls. The game ends when the snake crashes, with the player’s score based on how much food was collected. It is a console-based snake game using basic knowledge of C along with the following prerequisites:
1. Working C compiler and IDE.
2. For windows, we need <windows.h>. For linux, we need <unistd.h>. These libraries are generally installed by default.
3. We might need to install <console.h> library as it does not comes bundled with the standard C compiler.

The snake can be represented by the coordinates of its body stored in two arrays:
One Array for x-axis coordinates.
One Array for y-axis coordinates.

The head of the snake moves according to the user input:
W for up
S for down
A for left
D for right
while the rest of the body follows. When the snake eats some fruit, its length increases, and the coordinate array is updated. Collision detection is implemented to checking if the snake coordinates overlap (self-collision) or goes over the boundary limit (boundary collision).
