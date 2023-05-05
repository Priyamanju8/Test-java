import java.util.Scanner;

public class CountNumbers {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter a string: ");
        String str = input.nextLine();
        input.close();

        int count = 0;
        for (int i = 0; i < str.length(); i++) {
            if (Character.isDigit(str.charAt(i))) {
                count++;
                while (i < str.length() - 1 && Character.isDigit(str.charAt(i + 1))) {
                    i++;
                }
            }
        }
        System.out.println("Number of digits in the string: " + count);
    }
}
