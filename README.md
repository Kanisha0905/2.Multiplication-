# 2.Multiplication-
import java.util.Scanner;

public class MultiplyTwoNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();
        int product = num1 * num2;
        System.out.println("The product of " + num1 + " and " + num2 + " is: " + product);
        scanner.close();
    }
}
Output:
Enter the first number: 6
Enter the second number: 7
The product of 6 and 7 is: 42
