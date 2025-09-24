

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman word-guessing game in Python. Practice using strings, loops, conditionals, and user input to create an interactive game.

## 📝 Tasks

### 🛠️	Create the Hangman Game

#### Description
Write a Python program that lets a player guess letters to reveal a hidden word before running out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the user
- Display the current progress (e.g., _ _ a _ _ _)
- Track and display the number of incorrect guesses remaining
- End the game when the word is guessed or attempts are exhausted
- Show a win or lose message at the end

Example:
```
Word: _ _ _ _ _
Guess a letter: a
Incorrect! 5 attempts left.
Word: _ _ _ a _
Guess a letter: t
Correct!
...etc...
```

### 🛠️	Add Replay Option

#### Description
Enhance your game so that after finishing, the player can choose to play again with a new word.

#### Requirements
Completed program should:

- Ask the player if they want to play again after each game
- Start a new game with a different word if the player chooses to replay
- Exit if the player does not want to play again
