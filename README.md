# P43_NumbersFrom0to100

import java.util.Scanner;

public class P43_NumbersFrom0to100 {
    public static void main(String[] args) {

        Scanner vuvedi = new Scanner(System.in);

        System.out.print("Enter a number in the range [1...100]: ");
        int commandNumber = Integer.parseInt(vuvedi.nextLine());

        while (commandNumber < 1 || commandNumber > 100){

            System.out.println("Invalid number!");
            System.out.print("Enter a number in the range [1...100]: ");

            commandNumber = Integer.parseInt(vuvedi.nextLine());

        }

        System.out.println("The number is " + commandNumber);
    }


}
