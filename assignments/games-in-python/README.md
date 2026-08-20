# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable Hangman game in Python using loops, conditionals, strings, and user input. This assignment helps you practice tracking game state, validating guesses, and creating an interactive program from start to finish.

## 📝 Tasks

### 🛠️ Set Up the Hidden Word

#### Description
Create the game setup so a random word is chosen and displayed as hidden letters for the player to guess.

#### Requirements
Completed program should:

- Store a list of words and choose one at random.
- Show the hidden word using underscores, such as `_ _ _ _`.
- Accept a single letter guess from the player.
- Track letters that have already been guessed.
- Show a clear message when the player repeats a guess.

### 🛠️ Add Game Logic and End Conditions

#### Description
Build the main game loop so the player continues guessing until they solve the word or run out of attempts.

#### Requirements
Completed program should:

- Reveal correct letters in the hidden word as guesses are made.
- Reduce the remaining attempts when a guess is wrong.
- Keep playing until the word is fully guessed or attempts are exhausted.
- Display a final win or lose message with the correct word.
- Print the remaining attempts in a readable way during gameplay.
