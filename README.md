# Hangman Game in Java

# Overview

This is a simple implementation of the classic Hangman game in Java. Hangman is a word-guessing game where one player thinks of a word and the other player tries to guess it by suggesting letters within a certain number of guesses.


## How to Play

Run the Hangman.java file to start the game.

The computer will randomly select a word from its dictionary.

You'll be shown a series of dashes representing each letter in the word.

Guess letters by typing them in and pressing Enter.

If the letter is in the word, it will be revealed; if not, you'll lose a guess.

Keep guessing until you either solve the word or run out of guesses.

You win if you guess the word before running out of guesses, otherwise, the game is lost.

## Rules

You have a limited number of guesses (default: 6).

Only single alphabetic characters are valid guesses.

The game ignores case sensitivity, so 'a' and 'A' are treated the same.

Each incorrect guess leads to the drawing of a part of the hangman figure.

If the hangman figure is completed before the word is guessed, you lose.

## Features

Randomly selects a word from a predefined list.

Tracks and displays the letters already guessed.

Dynamically updates the hangman figure as guesses are made.

Displays the current progress in guessing the word.

## Files

Hangman.java: Contains the main Hangman game logic.

words.txt: Contains the dictionary of words from which the computer selects a word.

## Requirements

Java Development Kit (JDK) installed on your machine.

## Running the Game

Compile Hangman.java using javac Hangman.java.

Run the compiled file using java Hangman.
