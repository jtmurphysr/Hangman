# Hangman Game
This project is an implementation of the classic word-guessing game, Hangman, written in Python. The game randomly selects a word from a predefined list and challenges the player to guess it one letter at a time. The player has limited lives, which decrease with each incorrect guess.
## Features
1. **Random Word Selection**: The game uses `word_list` from the `hangman_words.py` file to randomly select a word for the player to guess.
2. **Visual Feedback**: Display of the hangman art stages from `hangman_art.py` dynamically updates based on lives left.
3. **Player Interaction**: Players are warned if they have already guessed a letter, and helpful feedback is provided for valid or incorrect guesses.
4. **Progress Tracking**: The word is displayed with placeholders that update as the user makes correct guesses.
5. **Win/Loss Conditions**: Players win if they guess all the letters correctly and lose if all their lives are exhausted, with final feedback showing them the word.

## File Structure
- **`hangman_art.py` **: Contains the ASCII art representing the hangman stages (`stages`) and the game logo (`logo`).
- **`hangman_words.py` **: Contains the word list (`word_list`) for random selection.

## How to Play
1. Start the game by running the script.
2. At the start, you'll see the game logo and a placeholder display for the word (e.g., `_ _ _` for a 3-letter word).
3. Guess one letter at a time:
    - If the guessed letter is in the word, it will be revealed in the correct position(s).
    - If it's incorrect, you'll lose a life, and a part of the hangman will be drawn.

4. The game ends:
    - **Win**: If all letters are guessed correctly before lives are exhausted.
    - **Lose**: If you run out of lives. The final word is revealed.


## Dependencies
- Python 3.6 or higher
- `hangman_art.py` and `hangman_words.py` in the same directory as the main script.

## Running the Project
1. Clone or download this repository.
2. Ensure `hangman_art.py` and `hangman_words.py` are in the same directory as the main script.
3. Run the script using the following command:
