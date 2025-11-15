This contain three mini python projects.

1.Number Guessing Game (Python)
A fun and interactive Python game where the computer thinks of a number between 1 and 100, and the player must guess it.
This is a great beginner project to understand loops, user input, random number generation, and error handling.
--Features
Random number generation between 1 and 100
Unlimited guessing attempts
Helpful hints:
“Too high!”
“Too low!”
Tracks total number of attempts
Handles invalid (non-integer) inputs
Simple and clean CLI interface
The program generates a random number using:
"random.randint(1, 100)"
The user keeps entering guesses in a loop.
The game gives feedback:
.Too high
.Too low
Correct guess
When the number is guessed correctly, the game ends and prints the total number of attempts.

------------------------------------------------------------------------------------------------------------
2. Random Password Generator

A Python script to generate secure random passwords with a mix of: 
Uppercase letters - Lowercase letters - Digits - Special characters
--Features
-   User defines password length
-   Ensures minimum complexity
-   Automatically shuffles characters for entropy

------------------------------------------------------------------------------------------------------------
3.Temperature Converter (Python)
A simple and interactive Python program that converts temperatures between Celsius, Fahrenheit, and Kelvin.
Ideal for beginners learning Python functions, conditional statements, and user input handling.
--Features
Convert Celsius → Fahrenheit
Convert Fahrenheit → Celsius
Convert Celsius → Kelvin
Convert Kelvin → Celsius
Convert Fahrenheit → Kelvin
Convert Kelvin → Fahrenheit
Error handling for invalid inputs
Clean and user-friendly CLI interface
--How It Works
The project uses individual conversion functions such as:
celsius_to_fahrenheit()
fahrenheit_to_celsius()
celsius_to_kelvin()
kelvin_to_celsius()
Higher-level conversion combos (e.g., Fahrenheit → Kelvin)
These are called based on the user's menu selection in the temperature_converter() function.
