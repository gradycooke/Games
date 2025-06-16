# Games

This repository is a growing collection of beginner-friendly Python games built using Jupyter Notebooks. 

## Current Projects

### Tic Tac Toe (`Tic_Tac_Toe.ipynb`)

A classic two-player game adapted for a single player against a basic AI. The game includes:

- 3×3 grid-based gameplay
- Turn-based interaction in the console
- Win detection for rows, columns, and diagonals
- Two AI modes: first-available or random move selection
- Input validation and error handling

---

### Random Number Guessing Game (`Random_Number_Game.ipynb`)

A simple but engaging game where the player tries to guess a randomly generated number within a limited number of attempts. Features include:

- Customizable upper limit for the random number
- User-defined number of guesses allowed
- Feedback for too-low or too-high guesses
- Handling of invalid inputs
- End-of-game feedback with the correct number revealed

---

### Hangman (`Hangman.ipynb`)

A console-based version of the classic Hangman game using the NLTK `words` corpus. 

- Word selection using `nltk.corpus.words`
- Filtering for length and character type
- Display of guessed letters and remaining attempts
- Input validation and replay-safe logic

---

## Tools Used

- Python (Standard Library)
- `random` — for word and number selection
- `input()` — for interactive console gameplay
- `try-except` — for input validation
- `nltk` — for natural language word data (Hangman only)

## Files

- `Tic_Tac_Toe.ipynb` — Single-player Tic Tac Toe with basic AI logic
- `Random_Number_Game.ipynb` — Customizable number guessing game with attempt limits
- `Hangman.ipynb` — Word-guessing game using the NLTK English word corpus

## Author

**Grady Cooke**  
[LinkedIn](https://www.linkedin.com/in/grady-cooke)  
[GitHub](https://github.com/gradycooke)
