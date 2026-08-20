# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable Hangman game in Python using loops, conditionals, strings, and user input. This assignment will help you practice tracking game state, validating input, and creating a complete interactive program.

## 📝 Tasks

### 🛠️ Set Up the Word Guessing Game

#### Description
Create the game setup so a random word is selected and the player sees a hidden version of it before making guesses.

#### Requirements
Completed program should:

- Store a list of words and choose one at random.
- Display the word as underscores, such as `_ _ _ _`.
- Keep track of letters that have already been guessed.
- Accept a single letter input from the player.
- Show a message when the guess is valid or repeated.

### 🛠️ Add Gameplay and Win/Lose Logic

#### Description
Build the main game loop so players continue guessing until they either solve the word or run out of attempts.

#### Requirements
Completed program should:

- Reveal correct letters in the hidden word as the player guesses.
- Reduce the remaining attempts for each incorrect guess.
- End the game when the player correctly guesses the full word.
- End the game when the player runs out of attempts.
- Display a final win or lose message that includes the secret word.
