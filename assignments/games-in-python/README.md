# 📘 Assignment: Hangman Game

## 🎯 Objective

Practice Python strings, loops, conditionals, lists, and user input by building a word-guessing game. Use the provided starter code to complete a playable Hangman game.

## 📝 Tasks

### 🛠️ Build a Hangman Game

#### Description
Complete `starter-code.py` to create a game that randomly selects a secret word and lets the player guess its letters. Reveal the word as guesses are made, and end the game when the player guesses the word or runs out of attempts.

#### Requirements
Completed program should:

- Randomly select one word from the provided `words` list.
- Start with no letters guessed and allow the player to enter one letter at a time.
- Display the current word progress using underscores for unguessed letters and show correctly guessed letters in their positions. For example, progress for `python` after guessing `p` and `t` is `p _ t _ _ _`.
- Track incorrect guesses and allow at most 6 incorrect guesses.
- Continue accepting guesses until the player guesses the entire word or reaches the incorrect-guess limit.
- Display a win message when the word is guessed, or a lose message that reveals the secret word when the incorrect-guess limit is reached.
