# Question-Four
Assignment
// This program displays all the multiples of 2, 3 and 7 within the range 71 to 150.

import java.util.Scanner;

public class MultiplesOf23and7 {

    public static void main(String[] args) {

        // Create a Scanner object to read user input.
        Scanner scanner = new Scanner(System.in);

        // Create a list to store the multiples.
        List<Integer> multiples = new ArrayList<>();

        // Loop through the numbers from 71 to 150.
        for (int number = 71; number <= 150; number++) {

            // Check if the number is divisible by 2, 3 and 7.
            if (number % 2 == 0 && number % 3 == 0 && number % 7 == 0) {

                // Add the number to the list.
                multiples.add(number);
            }
        }

        // Print the list of multiples.
        for (Integer multiple : multiples) {
            System.out.println(multiple);
        }
    }
}
