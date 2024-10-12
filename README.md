Project Overview
The Hangman game is designed to be a console-based game where players try to guess a randomly chosen word. Players are given a set number of guesses, and incorrect guesses reduce the number of guesses left. Additionally, a help system is available that reveals letters but penalizes the player by removing additional guesses.

How to Play
The game starts by randomly selecting a word from a list of words.
The player has 10 guesses to figure out the word.
For each guess:
If the guessed letter is in the word, it is revealed in the word’s progress.
If the guessed letter is not in the word:
If it is a consonant, the player loses 1 guess.
If it is a vowel, the player loses 2 guesses.
Players can use the help feature by typing !, which reveals a letter but costs 3 guesses.
The player wins if they guess the word before running out of guesses.
Files
hangman.py: The main script that runs the Hangman game.
words.txt: A file that contains a list of words from which the game chooses the secret word.
Installation
Clone the repository or download the script to your local machine.
Make sure you have Python installed (version 3.x recommended).
Ensure that words.txt is in the same directory as hangman.py.
Usage
Open a terminal.

Navigate to the directory where hangman.py is located.

Run the following command to start the game:

bash
Copy code
python hangman.py
Follow the on-screen instructions to guess letters and try to win the game.

Features
Standard Hangman game: Play the traditional guessing game with letters.
Help mode: Type ! to reveal a missing letter, at the cost of 3 guesses.
Customizable word list: Modify words.txt to add or remove words.
Score Calculation: The game provides a score based on remaining guesses and the number of unique letters in the word.
