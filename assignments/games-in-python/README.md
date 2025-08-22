# 📘 Assignment: Games in Python

## 🎯 Objective

Build a classic Hangman game in Python to practice string manipulation, loops, conditionals, and user input. By completing this assignment, you will learn how to manage game state and interact with users through the console.

## 📝 Tasks

### 🛠️	Create the Hangman Game

#### Description
Write a Python program that lets a player guess letters to reveal a hidden word. The game should randomly select a word from a list, track guesses, and display progress after each guess.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the word as underscores (_ _ _) for unguessed letters
- Accept single-letter guesses from the user
- Track and display the number of incorrect guesses remaining
- Reveal correctly guessed letters in their positions
- End the game when the word is fully guessed or attempts run out
- Show a win message if the player guesses the word, or a lose message if attempts are exhausted

**Example:**
```plaintext
Word: _ _ _ _ _
Guess a letter: a
Incorrect! Attempts left: 5
Word: _ a _ _ _
Guess a letter: t
Correct!
...
```

### 🛠️	Enhance the Game Experience

#### Description
Add features to make the game more user-friendly and engaging.

#### Requirements
Completed program should:

- Prevent repeated guesses of the same letter
- Show all guessed letters so far
- Handle invalid input (e.g., numbers, symbols, multiple letters)
- Allow the player to play again after finishing
