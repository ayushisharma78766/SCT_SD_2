# Number Guessing Game

## Overview
The **Number Guessing Game** is a simple Java terminal-based game where the computer randomly selects a number and the player tries to guess it. The game provides feedback for each guess, indicating whether the guess is too high, too low, or correct. It also keeps track of the number of attempts the player takes to guess the correct number.

This project is ideal for beginners who want to practice **Java programming**, **loops**, **conditional statements**, and **user input handling**.

---

## Features
- Generates a random number between **1 and 100**.
- Prompts the player to input their guess.
- Gives feedback if the guess is **too high** or **too low**.
- Tracks the number of attempts.
- Congratulates the player once the correct number is guessed.

---

## How to Play
1. Run the program.
2. The computer selects a random number between 1 and 100.
3. Enter your guesses in the terminal.
4. The program will tell you if your guess is too high or too low.
5. Keep guessing until you find the correct number.
6. The program will display the total number of attempts.

---

## Prerequisites
- **Java Development Kit (JDK) 8 or above** installed.
- A **terminal/command prompt** to run the Java program.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/NUMBER-GUESSING-GAME.git
Navigate to the project directory:

bash
Copy code
cd NUMBER-GUESSING-GAME
Compile the Java program:

bash
Copy code
javac NumberGuessingGame.java
Run the program:

bash
Copy code
java NumberGuessingGame
Example Gameplay
mathematica
Copy code
Welcome to the Number Guessing Game!
I have selected a number between 1 and 100.
Can you guess it?
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 62
Congratulations! You guessed the number in 3 attempts.
Code Structure
NumberGuessingGame.java → Main program containing the game logic.

Generates a random number.

Takes user input.

Compares guesses and gives feedback.

Tracks number of attempts.

Skills Practiced
Java basics (loops, conditionals, input/output)

Random number generation (java.util.Random)

User input handling (java.util.Scanner)

Basic game logic

Author
Ayushi Sharma

GitHub: https://github.com/ayushisharma78766

Internship: SkillCraft Internship - SCT_SD_2

