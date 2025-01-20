# switch-case
import java.util.Scanner;
public class DayDescription {
public static void main(String[] args) {
  Scanner scanner = new Scanner(System.in);
  System.out.print("Enter a number (1-5): ");
   int day = scanner.nextInt();
        switch (day) {
            case 1:
                System.out.println("Good day");
                break;
            case 2:
                System.out.println("Average day");
                break;
            case 3:
                System.out.println("Good day");
                break;
            case 4:
                System.out.println("Bad day");
                break;
            case 5:
                System.out.println("Good day");
                break;
            default:
                System.out.println("Invalid input! Please enter a number between 1 and 5.");
        }
    }
}
