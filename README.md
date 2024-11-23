## Introduction
This is a simple game of Hangman. It is my first project ever, after a month of studying Python. The game is only text-based in the command line. It has a simple functionality that can be expanded.
I mainly tried to test my current skills, and write a coherent and somehow clean code. The code has docstrings and is trying to follow the 'separation of concerns' principle with functions.
There might be some small updates in the future, but this is more of a demonstration of my skill and a way to learn things.

## Functionality
- The computer picks a random word from the Wonderwords module and presents the player with blank spaces equal to the length of the word.
- The player tries to guess the letters of the word one by one.
- If the player guesses a letter that is not present in the word, the computer draws a piece of the Hangman figure.
- Once fully drawn, the player loses. The code repeats but gives the option to the player to exit after the game.
- The player wins if he correctly guesses all the letters in the word, therefore revealing the whole word.
- The player input is protected to only insert valid parameters. The game also has some role-playing text for some flavour.

## Installation
No installation. It is a python file, so must be run in a Python interpreter or terminal. The game starts automatically through the start() function.
