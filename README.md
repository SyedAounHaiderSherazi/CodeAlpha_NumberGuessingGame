# Number Guessing Game 🎯

A simple C++ program where the computer randomly selects a number, and the player has to guess it with hints like "too high" or "too low". The goal is to guess the correct number in the fewest attempts possible.

## Features
- The computer generates a random number between 1 and 100.
- The player is prompted to guess the number.
- Hints are provided if the guess is too high or too low.
- The number of attempts is tracked and displayed when the correct guess is made.

## How to Play
1. Run the program.
2. Guess a number between 1 and 100.
3. The game will give feedback on whether your guess is too high, too low, or correct.
4. Continue guessing until you find the correct number.
5. The game will display how many attempts it took you to guess correctly.

## How to Compile and Run the Program

### Requirements
- A C++ compiler (e.g., GCC, Clang, MSVC)
- Basic knowledge of C++ programming

### Compile
To compile the program, run the following command in your terminal:

```bash
g++ -o guessing_game guessing_game.cpp
