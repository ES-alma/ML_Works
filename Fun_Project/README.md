Number Guessing Game

##Description

A classic interactive logic game built in Python. The objective is to guess a randomly generated number within a set amount of attempts. The game provides tiered feedback based on how close the player is to the target, adding an extra layer of strategy compared to standard "high/low" games.


##Logic Flow

The game uses a while loop to manage turns and a try-except block to ensure the program doesn't crash if a user accidentally types a letter instead of a number.

Huge Difference:  n> 15 (n= diference between the guess and the target_number) units away. Standard: 5 to 15 units away. Nearly there: n< 5 units away.

##Steps Performed


1. Game Initialization: Setting the target_number and the maximum number of allowed tries.
2. Input Handling: Capturing user guesses and converting strings to integers.
3. Conditional Feedback: Using if/elif logic to calculate the difference and print helpful hints.
4. Win/Loss States: Checking if the player guessed correctly or ran out of lives.

##Results

User Friendly: The "Nearly there" hint helps players narrow down the final digits quickly.
Robust: The code handles ValueError gracefully, allowing the user to try again without losing a turn.
##Tools Used
Python 


##Conclusion 

This project demonstrates fundamental programming concepts like loops, error handling, and conditional branching. It's a lightweight, fun console application that provides a smooth user experience.
