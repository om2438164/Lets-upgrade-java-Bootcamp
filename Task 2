@@ Finds and display maximum number in array and display its position

import java.util.Scanner;
public class MaximumNumber {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the size of the array: ");
        int size = input.nextInt();

        int[] array = new int[size];
        System.out.println("Enter the values of the array elements:");
        for (int i = 0; i < size; i++) {
            array[i] = input.nextInt();
        }

        int maxNumber = array[0];
        int maxIndex = 0;

        for (int i = 1; i < size; i++) {
            if (array[i] > maxNumber) {
                maxNumber = array[i];
                maxIndex = i;
            }
        }

        System.out.println("Maximum Number: " + maxNumber);
        System.out.println("Position of First Occurrence: " + (maxIndex + 1));
    }
}
