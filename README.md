# Wordle-project

This project is a word-guessing game implemented in C, consisting of three files: main.c, yorkle.h, and yorkle.c.

The main.c file contains the primary logic of the game. It loads a list of valid words, the answer for today's game, and the player's stats from external files. It then prompts the player to guess the word in a series of attempts. The player's attempts are compared to the correct answer and appropriate feedback is provided. Finally, the player's stats are updated and saved to an external file.

The yorkle.h file is a header file that contains declarations of functions, constants, and data structures used in the game. It provides an interface between the main.c and yorkle.c files.

The yorkle.c file contains the implementation of the functions declared in yorkle.h. These functions handle various tasks such as loading valid words, loading the answer for the day, managing player stats, reading and validating player attempts, comparing the attempts with the correct answer, printing attempt results, and saving player stats.

In summary, this project is a word-guessing game where the player tries to guess a word within a limited number of attempts. The game makes use of external files to store and load game data and keeps track of player statistics.
