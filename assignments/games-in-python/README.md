# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable Hangman game in Python using strings, loops, conditionals, random selection, and user input. Practice tracking game state and validating guesses in an interactive program.

## 📝 Tasks

### 🛠️ Set Up the Hidden Word

#### Description
Create the game setup so a word is selected at random and displayed as hidden letters for the player to guess.

#### Requirements
Completed program should:

- Store multiple words in a predefined list and select one at random.
- Display the hidden word using underscores, such as `_ _ _ _`.
- Accept a single letter guess from the player.
- Track letters that have already been guessed.

### 🛠️ Add Gameplay and End Conditions

#### Description
Build the main game loop so the player continues guessing until the word is solved or the available attempts run out.

#### Requirements
Completed program should:

- Reveal correct letters in the hidden word.
- Track incorrect guesses and the number of attempts remaining.
- Prevent repeated guesses from changing the game state incorrectly.
- End when the player guesses the full word or runs out of attempts.
- Display a clear win or lose message and reveal the correct word.
