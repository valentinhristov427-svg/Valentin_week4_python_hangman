# Valentin's Hangman Game 

## Overview 

This is my first git repository, built to house my simple version of the well known Hangman game for the Rockborne Data training programme. 

## Features 

- The game has an easy and a hard difficulty, differentiated by the word length and complexity.
- The game runs on a GUI built with tkinter, where button clicks activate functions. This is an upgrade from the original build which worked in the Python console.
- Featuring an actual updating hangman!
- Robust input validation system, only accepts single letters. Soft fails other inputs types.
- Global statistics tracking per session.
- Play again button. Feel free to play as many rounds as your heart desires!

## How to play

1. Run "Valentin's Hangman.py"
2. Choose difficulty by pressing buttons
3. Type single letter into submission box
4. Continue playing until your hangman needs have been satisfied!

--- 

### Function overview

- word_picking_func -> selects a random word from a list based on difficulty chosen
- letter_checking_function -> checks a guessed letter and updates user's progress
- letter_validation_function -> initialises a new round, activatd upon difficulty selection button press
- guess_letter -> the main function that deals with user input, passes input through leter_validation and then letter_checking to update project.
- draw_body_part -> responsible for drawing the bodyparts of the hangman

### Future Improvements

- Sound effects
- A nicer GUI
- More difficulty levels
- Ability to guess the full word at any point in the game, perhaps at the cost of two lives, or a separate currency.

## NOTE ON AI USE

AI was primarily used for debugging and consulting on the tkinter library. The AI was prompted to not generate complete lines of code but to instead hint at solutions and suggest functions which could be of service. 

No AI was used throughout the development of versions 1.0.0 and 1.1.0 (Python console native versions).

AI was asked to give me a tutorial and a walk through of the features of Tkinter it thought would be relevant for this project, aswell as how the library works in general. If any code was written directly by AI it is labelled in the .py file using ### CAPITAL LETTERS ### in the comments. 




