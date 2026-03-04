# Number Guessing Game

A simple and interactive number guessing game built with Python. The computer randomly selects a number between 1 and 100, and you try to guess it in as few attempts as possible!

## Features

- **Random Number Generation**: The computer picks a random number between 1 and 100
- **Interactive Gameplay**: Real-time feedback on your guesses (too high, too low, or correct)
- **Attempt Counter**: Tracks the number of attempts it takes you to guess the number
- **Input Validation**: Handles invalid inputs gracefully with error messages
- **Simple Interface**: Easy-to-use command-line interface

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
```bash
git clone https://github.com/JoelJacob569/Number_Guessing_Game.git
cd Number_Guessing_Game
```

2. No additional dependencies are required - the game only uses Python's built-in `random` module.

## Usage

Run the game using Python:
```bash
python numbergame.py
```

Then follow the on-screen prompts:
1. The game will tell you it has selected a number between 1 and 100
2. Enter your guess when prompted
3. The game will tell you if your guess is too low or too high
4. Keep guessing until you find the correct number
5. Once you guess correctly, the game displays your total number of attempts

### Example Gameplay
```
Welcome to the Number Game!
I have selected a random number between 1 and 100.
Try to guess the number in as few attempts as possible.
Enter your guess: 50
Too high! Try again.
Enter your guess: 25
Too low! Try again.
Enter your guess: 37
Congratulations! You've guessed the number 37 in 3 attempts.
```

## How It Works

The game uses the following logic:
- Generates a random integer between 1 and 100
- Continuously prompts the user for guesses until the correct number is found
- Compares each guess to the target number and provides feedback
- Counts the number of attempts and displays it when the game is won
- Includes error handling for non-integer inputs

## Try It Out!

Test your guessing skills and see how few attempts it takes you to find the number. Can you beat your personal record?

## License

This project is open source and available under the MIT License.

## Author

Created by JoelJacob569