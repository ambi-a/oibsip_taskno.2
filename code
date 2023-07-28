import java.util.Scanner;

public class GFG {

    public static void guessingNumberGame() {

    // Scanner Class
    Scanner sc = new Scanner(System.in);

    // Generate the numbers
    int number = 1 + (int)(100 * Math.random());

    // Given K trials
    int MAX_ATTEMPTS = 10;

    // Initialize the variable i
    int i = 0;
    int points = 0;

    System.out.println("A number is chosen between 1 to 100. Guess the number within 10 trials.");

    // Iterate over the MAX_ATTEMPTS
    for (i = 0; i < MAX_ATTEMPTS; i++) {

        System.out.println("Guess the number:");

        // Take input for guessing
        int guess = sc.nextInt();

        // If the number is guessed
        if (number == guess) {
            System.out.println("Congratulations! You guessed the number.");
            points++;
            break;
        } else if (number > guess && i != MAX_ATTEMPTS - 1) {
            System.out.println("The number is greater than " + guess);
        } else if (number < guess && i != MAX_ATTEMPTS - 1) {
            System.out.println("The number is less than " + guess);
        }
    }

    if (i == MAX_ATTEMPTS) {
        System.out.println("You have exhausted K trials.");
        System.out.println("The number was " + number);
    } else {
        System.out.println("You scored " + points + " points.");
    }
}

    public static void main(String arg[]) {

        // Function Call
        guessingNumberGame();
    }
}
