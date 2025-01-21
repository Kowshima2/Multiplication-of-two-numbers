# Multiplication-of-two-numbers
import java.util.Scanner;

public class MultiplicationOfTwoNumbers {
    public static void main(String[] args) {
        // Create a Scanner object for user input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the first number
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        // Prompt the user to enter the second number
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        // Calculate the product
        int product = num1 * num2;

        // Display the result
        System.out.println("The product of " + num1 + " and " + num2 + " is: " + product);

        // Close the scanner
        scanner.close();
    }

Output 

Enter the first number: 4
Enter the second number: 5
The product of 4 and 5 is: 20
