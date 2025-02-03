# Mastermind Game

Welcome to the **Mastermind Game** 🎮! This is a classic code-breaking game where you try to guess a secret sequence of colors in a limited number of attempts. It supports multiple difficulty levels, a demo mode, user sign-up, login, and high score tracking!

## Table of Contents
- [Game Description](#game-description)
- [Features](#features)
- [Gameplay Instructions](#gameplay-instructions)
- [User Management](#user-management)
- [High Score Tracking](#high-score-tracking)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)

## Game Description

Mastermind is a puzzle game where the goal is to break a secret code composed of four colored pegs. The player has 5 attempts to guess the correct code. After each guess, feedback is given as follows:
- **⬜** - Correct color in the correct position
- **⬛** - Correct color in the wrong position
- **X** - Incorrect color

You can choose between **Easy** or **Hard** levels, or try the **Demo** mode to learn how the game works.

## Features

- 🎮 **Multiple Difficulty Levels**: Choose between Easy and Hard levels.
- 🆔 **User Signup and Login**: Sign up for an account and log in to play.
- 🏆 **High Score Tracking**: View and track your best scores for each level.
- 💡 **Demo Mode**: A sample round to understand the gameplay before playing.

## Gameplay Instructions

1. **Sign up**: Create an account with a username and password.
2. **Login**: Login with your username and password to start playing.
3. **Choose Difficulty**: Select a difficulty (Easy/Hard) or try the Demo mode.
4. **Make Guesses**: In each attempt, guess a combination of colors.
5. **Feedback**: Get feedback for each guess and try to crack the code in 5 attempts.

## User Management

- **Sign-up**: Enter a unique username and password. If the username already exists, you'll be prompted to choose another.
- **Login**: Enter your username and password to start the game.
- **High Score**: After completing a game, your score will be saved if it's the highest for that level.

## High Score Tracking

The high scores are stored in a file and associated with each user and difficulty level. You can view your high scores by entering your username.

## Technologies Used

- **Java**: The game is written in Java.
- **File Handling**: User credentials and high scores are stored in text files (`users.txt` and `user_highscores.txt`).

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Compile and run the `Main.java` file.
4. Play the game by following the on-screen prompts.

### Example

To compile and run:

```bash
javac Main.java
java Main
