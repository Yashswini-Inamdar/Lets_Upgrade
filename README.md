# Lets_Upgrade
# Assignments of Java Essential bootcamp by Lets Upgrade
import java.util.Scanner;

public class PositiveNegativeNumber {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter a number: ");
        double number = input.nextDouble();

        if(number > 0) {
            System.out.println("The number is positive.");
        } else if(number < 0) {
            System.out.println("The number is negative.");
        } else {
            System.out.println("The number is zero.");
        }
    }

}

