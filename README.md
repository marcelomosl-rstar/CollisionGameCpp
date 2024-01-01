# Circle and Square Game

## Overview

This simple game is built using the [Raylib](https://www.raylib.com/) library and involves a blue circle and a purple square moving on the screen. The objective is to avoid a collision between the circle and the square. The player can control the horizontal movement of the circle using the arrow keys.

## Game Rules

1. The blue circle starts at the top of the window and moves horizontally based on the player's input.
2. The purple square moves vertically from the top to the bottom of the window and bounces back when reaching the edges.
3. The game ends if the square collides with the circle.

## Controls

- **Left Arrow Key**: Move the circle to the left.
- **Right Arrow Key**: Move the circle to the right.

## How to Play

1. Run the game executable.
2. Use the arrow keys to move the blue circle left or right.
3. Try to avoid a collision between the blue circle and the purple square.
4. If a collision occurs, the game will display a "Game Over" message in red.

## Building the Game

To build and run the game, ensure you have the Raylib library installed. You can find instructions on how to install Raylib [here](https://www.raylib.com/).

After installing Raylib, compile the game source code using a C compiler, such as GCC, and link it with the Raylib library. For example:

```bash
gcc main.c -o CircleAndSquareGame -lraylib

