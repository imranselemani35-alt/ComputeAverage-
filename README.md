# ComputeAverage-
// the program calculate the average of four numbers
import java.util.Scanner; // bringing in scanner class to allow user input

public class ComputeAverage {
    public static void main(String[] args) {
        // make a Scanner  get input from the user
        Scanner input = new Scanner(System.in);

// tell the user to enter the first number
        System.out.print("Enter first number: ");
        double num1 = input.nextDouble(); // keeping the first number

        // tell the user for the second number to be entered
        System.out.print("Enter second number: ");
        double num2 = input.nextDouble(); // keeping the second number

        // tell the user for the third number to be entered
        System.out.print("Enter third number: ");
        double num3 = input.nextDouble(); // keeping the third number

        // tell the user for the fourth number to be entered
        System.out.print("Enter fourth number: ");
        double num4 = input.nextDouble(); // keeping the fourth number

   // this time computing the average of the four numbers
        double average = (num1 + num2 + num3 + num4) / 4;

        // now showing the final result or outcome to the user
        System.out.println("The average of the four numbers is: " + average);

        // now ending the Scanner to avoid resource leaks
        input.close();

        // End of program
    }
}
