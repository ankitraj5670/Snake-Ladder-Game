# Snake and Ladder Game

## Introduction
This is a simple implementation of the classic Snake and Ladder game in C programming language. The game allows two players to take turns rolling a dice and moving their respective tokens on the board. The board contains snakes and ladders that can either help or hinder the players' progress.

## Features
- Two players (Player 1 represented by RED color and Player 2 represented by GREEN color) take turns to roll a dice and move their tokens on the board.
- Snakes and ladders are randomly placed on the board.
- If a player lands on a square with the head of a snake, they move back to the square's tail.
- If a player lands on a square with the base of a ladder, they move forward to the square's top.
- The game ends when one of the players reaches the last square (100).
- Players have an option to play again or exit the game after a winner is declared.

## How to Play
1. Compile the program using any C compiler.
2. Run the executable.
3. Follow the on-screen instructions to roll the dice.
4. The players take turns to roll the dice and move their tokens accordingly.
5. The game continues until one of the players reaches the last square (100).
6. After a winner is declared, the players have the option to play again or exit the game.

## Note
- This program uses ANSI escape codes for colorful output. Make sure your terminal supports ANSI escape codes for proper display.
- The game might not work correctly in all terminal environments due to the use of `system("cls")` to clear the screen, which is specific to Windows systems. You may need to modify this part if you're using a different operating system.
