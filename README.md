# Wordle Clone in JavaScript

## Overview

Welcome to my Wordle Clone project! This project is a JavaScript implementation of the popular word guessing game Wordle. The goal of this project is to demonstrate my technical abilities and showcase it as part of my JavaScript project portfolio. This implementation uses Node.js with the `chalk` library for colorful console output and `prompt-sync` for synchronous user input.

## Features

- **Interactive Command Line Interface**: The game runs in the terminal and interacts with the user through text input.
- **Word Validation**: Ensures the user input is a valid 5-letter word.
- **Color-coded Feedback**: Provides feedback on each guess using colors to indicate correct, misplaced, and incorrect letters.
- **Efficient Letter State Tracking**: Uses maps and arrays to efficiently track and compare letter states between the user input and the solution.

## How to Play

Follow the prompt to enter your 5-letter guess. The game will provide feedback using the following color codes:
   - **Green**: The letter is correct and in the correct position.
   - **Yellow**: The letter is correct but in the wrong position.
   - **Red**: The letter is incorrect.

## Code Breakdown

### Main Game Loop

The main game loop prompts the user for a 5-letter word until the correct solution is guessed. It validates the input and provides feedback using helper functions.

### Helper Functions

#### `getWordState`

This function compares the user input with the solution and returns an array of letter states.

#### `getLetterState`

This function determines the state of each letter (correct, misplaced, incorrect).

#### `getLetterCountMap`

This function creates a map of letter counts in the solution word.

#### `printUserSolution`

This function prints the user's guess with color-coded feedback.

## Conclusion

This Wordle Clone project demonstrates my ability to develop interactive command line applications using JavaScript. It showcases my skills in:
- JavaScript programming
- Problem-solving and algorithm development
- Using external libraries to enhance functionality

Feel free to reach out if you have any questions or feedback. Thank you for checking out my project!
