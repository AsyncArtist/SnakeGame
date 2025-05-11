# Snake Game

## Overview
This is a console-based Snake Game implemented in C#. The game is designed to run in a terminal and provides a simple yet engaging gameplay experience. The player controls a snake that grows in size as it consumes food, and the objective is to avoid colliding with the walls or the snake's own body.

## Features
- Classic snake gameplay.
- Console-based interface.
- Dynamic snake growth.
- Game over detection when the snake collides with itself or the walls.

## Prerequisites
- .NET 9.0 SDK or later installed on your system.

## How to Run
1. Clone or download this repository to your local machine.
2. Open a terminal and navigate to the `SnakeGame_Console` directory.
3. Build the project using the following command:
```bash
dotnet build
```
4. Run the game using the following command:
```bash
dotnet run
```

## Project Structure
- `Program.cs`: Contains the main entry point of the application.
- `Snake.cs`: Handles the logic for the snake's movement and growth.
- `ConsoleHelper.cs`: Provides utility functions for console operations.
- `Enums.cs`: Defines enumerations used in the game.

## Gameplay Instructions
- Use the arrow keys to control the snake's direction.
- Eat the food to grow longer.
- Avoid colliding with the walls or your own tail.
- The game ends when the snake collides with itself or the walls.