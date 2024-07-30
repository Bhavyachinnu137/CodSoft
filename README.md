#TASK1 Guessing Game

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

git clone (https://github.com/Bhavyachinnu137/CodSoft/blob/main/.gitignore)

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


#TASK2 Student Grades

Student Grades

This is a simple Java program that calculates the total marks, average percentage, and grade for a student based on the marks obtained in various subjects. The program takes the number of subjects and the marks for each subject as input from the user.

How to Use

The program prompts the user to enter the number of subjects.

The user is then prompted to enter the marks for each subject.

The program calculates the total marks, average percentage, and determines the grade based on the average percentage.

The results are displayed to the user.

Grade Criteria

A: Average Percentage >= 90%

B: Average Percentage >= 80% and < 90%

C: Average Percentage >= 70% and < 80%

D: Average Percentage >= 60% and < 70%

F: Average Percentage < 60%

Running the Program

1.Clone the repository to your local machine.

git clone https://github.com/yourusername/student-grades.git

2.Navigate to the project directory.

cd student-grades

3.Compile the Java code.

javac StudentGrades.java

4.Run the compiled Java program.

java StudentGrades

Example:

Enter the number of subjects: 3

Enter the marks for subject 1: 85

Enter the marks for subject 2: 90

Enter the marks for subject 3: 78

Total Marks: 253

Average Percentage: 84.33333333333333%

Grade: B


#TASK3 ATM MACHINE

ATM Simulation

This is a simple ATM simulation program implemented in Java. The program allows users to check their balance, deposit funds, and withdraw funds from their bank account through a menu-driven interface.

Features

Check balance: View the current balance of the bank account.

Deposit funds: Add a specified amount to the bank account.

Withdraw funds: Withdraw a specified amount from the bank account.


Sure! Here's a README file for your ATM program:

ATM Simulation
This is a simple ATM simulation program implemented in Java. The program allows users to check their balance, deposit funds, and withdraw funds from their bank account through a menu-driven interface.

Features
Check balance: View the current balance of the bank account.

Deposit funds: Add a specified amount to the bank account.

Withdraw funds: Withdraw a specified amount from the bank account.

Getting Started

Prerequisites
Java Development Kit (JDK) installed on your machine.

Running the Program

1.Clone the repository to your local machine.

git clone https://github.com/yourusername/atm-simulation.git

2.Navigate to the project directory.

cd atm-simulation

3.Compile the Java code.

javac BankAccount.java ATM.java

4.Run the compiled Java program.

java ATM

Example

ATM Menu:

1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 1
Current Balance: 1000.00

ATM Menu:
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 2
Enter amount to deposit: 200
Deposited: 200.00

ATM Menu:
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 3
Enter amount to withdraw: 150
Withdrew: 150.00

ATM Menu:
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 4
Thank you for using the ATM. Goodbye!



