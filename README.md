# oibsip_taskno.2
Guessing Number Game:
The "Guessing Number Game" is a simple Java console-based application that allows users to play a guessing game. The program generates a random number between 1 and 100 and challenges the player to guess the number within a limited number of attempts (default is 10). The player earns points by correctly guessing the number and can win the game if they guess it within the allowed attempts.


How to Play:
Clone the repository to your local machine or download the GuessingNumberGame.java file.


Compile the Java code:
javac GuessingNumberGame.java


Run the program:
java GuessingNumberGame
The program will display a welcome message and instructions, informing the player that a number has been chosen between 1 and 100. The player needs to guess the number within 10 attempts.
Enter your guess when prompted and press Enter.
The program will provide feedback on whether the guessed number is higher or lower than the target number. If the guessed number is correct, the player wins the game.
If the player exhausts all the allowed attempts without guessing the correct number, the game ends, and the target number is revealed.
The game will display the player's final score, which corresponds to the number of correct guesses made.


Customization:
To change the range of numbers the program can choose from, you can modify the line: int number = 1 + (int)(100 * Math.random());. 
For example, to choose a number between 1 and 25, use: int number = 1 + (int)(35 * Math.random());.
To adjust the maximum number of attempts allowed, change the value of the MAX_ATTEMPTS variable: int MAX_ATTEMPTS = 10;.
If you want you can change them to any number you wish.
