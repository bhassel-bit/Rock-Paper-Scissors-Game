# Rock Paper Scissors Game (Java)

## Overview
This is a simple **Rock Paper Scissors** game built in Java. The player chooses Rock, Paper, or Scissors, and the computer makes a random selection. The program compares both choices and announces whether the player wins, the computer wins, or the game is a tie.

This project was created to practice Java fundamentals such as user input, variables, conditional statements, logical operators, and random number generation.

## How the Game Works
1. The program welcomes the player and asks for a choice:
   - `0` = Rock
   - `1` = Paper
   - `2` = Scissors
2. The player enters a number.
3. The computer randomly selects a number from `0` to `2`.
4. The program compares the selections and displays the result.

### Winning Rules
- Rock beats Scissors (`0` beats `2`).
- Paper beats Rock (`1` beats `0`).
- Scissors beats Paper (`2` beats `1`).
- Matching choices result in a tie.

## Technologies Used
- **Java**
- `Scanner` for reading user input
- `Random` for generating the computer's choice

## How to Run
1. Open the project in **Eclipse** or another Java IDE.
2. Make sure `RockPaperScissor.java` is in the `day4` package (as declared in the source file).
3. Run the `RockPaperScissor` class as a Java application.
4. Enter `0`, `1`, or `2` in the console and view the outcome.

## Java Concepts Practiced
- **Variables and data types:** storing player and computer selections as `int` values.
- **User input:** using `Scanner` and `nextInt()`.
- **Random numbers:** using `new Random().nextInt(3)` to generate `0`, `1`, or `2`.
- **Conditionals:** using `if`, `else if`, and `else` to determine the winner.
- **Logical operators:** using `||` (OR) and `&&` (AND) to check winning combinations.
- **Console output:** using `System.out.println()`.

## Current Limitations
- The game runs for a single round each time the application starts.
- The program displays an invalid-choice message when a number outside `0`–`2` is entered, but the current code does **not** stop before attempting the rest of the game.
- Entering text instead of a number is not handled.

## Possible Future Improvements
- Stop the game immediately after invalid input.
- Let players play multiple rounds without restarting.
- Display the computer's choice as Rock, Paper, or Scissors instead of a number.
- Keep track of wins, losses, and ties.
