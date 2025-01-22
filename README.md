Password Generator

Description --
This project is a Password Generator built with Python. It allows users to create secure, randomized passwords by specifying the number of letters, symbols, and numbers they want in the password. The script then generates a password with the desired configuration and ensures the characters are shuffled for additional security.

Features --

Generate passwords with:
Customizable letters (uppercase and lowercase).
Customizable symbols (e.g., !, @, #).
Customizable numbers (e.g., 0-9).

Ensures the final password is shuffled for randomness.
Simple and interactive command-line interface.

How to Use --

Run the script in a Python environment.

Follow the prompts:
Enter the number of letters, symbols, and numbers you want in your password.

View your randomly generated password.

Requirements --
Python 3.x installed on your system.

Modules Used --
random: Used for selecting random characters and shuffling the password list.

How It Works --

The program prompts the user to enter the desired number of:
Letters: Randomly selected from a predefined list of uppercase and lowercase letters.
Symbols: Randomly selected from a predefined list of common symbols.
Numbers: Randomly selected from a predefined list of digits.

The selected characters are stored in a list.
The list is shuffled for randomness.
The characters are joined to form the final password, which is displayed to the user.
