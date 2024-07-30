Guessing Game

This is a simple number guessing game implemented in Java. The player tries to guess a randomly generated number between 1 and 100. The player has a limited number of attempts to guess the correct number, and the score is based on the number of attempts remaining when the number is guessed correctly.

How to Play

The game starts by generating a random number between 1 and 100.
The player has 10 attempts to guess the number.
After each guess, the game will provide feedback:
"Too low! Try again." if the guess is less than the target number.
"Too high! Try again." if the guess is greater than the target number.
"Correct! You've guessed the number." if the guess is equal to the target number.
If the player guesses the number correctly, the score is updated based on the remaining attempts.
The player can choose to play another round or end the game.
The game will display the total score and the number of rounds played at the end.

Getting Started

Prerequisites
Java Development Kit (JDK) installed on your machine.

Running the Game

1.Clone the repository to your local machine
git clone https://github.com/yourusername/guessing-game.git
2.Navigate to the project directory.
cd guessing-game
3.Compile the Java code.
javac GuessingGame.java
4.Run the compiled Java program.
java GuessingGame

Example

New Round! Guess the number between 1 and 100. You have 10 attempts.
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 60
Correct! You've guessed the number.
Do you want to play another round? (yes/no): no

Game Over! You played 1 rounds and your score is: 8
