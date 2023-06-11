# Mastermind Game in Ruby

This repository contains two Ruby scripts to simulate the classic code-breaking game, Mastermind.

## Files Description

**1. mastermind_player.rb:** This script allows a human player to play against the computer. The computer generates a random 4-digit sequence using numbers from 1 to 6, and the player has to guess this sequence. After each guess, the player receives feedback on how many digits are in the correct position and how many digits are correct but in the wrong position.

**2. mastermind_bot.rb:** This script enables a bot to play the game against the computer. The bot uses a strategy to guess the computer's secret sequence based on feedback received from previous guesses.

## How to Run the Scripts

1. Ensure Ruby is installed on your machine.

2. Clone this repository to your local machine.

3. Navigate to the directory containing the scripts.

4. Run ruby mastermind_player.rb to play as a human or ruby mastermind_bot.rb to see the bot in action.

## Game Rules

- The computer selects a random sequence of 4 numbers between 1 and 6.
- You have to guess this sequence. Each guess should be a 4-digit number, each digit ranging from 1 to 6.
- After each guess, you will receive feedback in the form of:
    - The number of digits in the correct position.
    - The number of digits that are correct but in the wrong position.
    - You continue guessing until you correctly guess the sequence or exhaust your trials.
