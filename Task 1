
@@ without using switch case

import java.util.Scanner;
public class GradeCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter your test score: ");
        int score = scanner.nextInt();

        if (score >= 0 && score <= 100) {
            String grade;
            if (score >= 90) {
                grade = "A";
            } else if (score >= 80) {
                grade = "B";
            } else if (score >= 70) {
                grade = "C";
            } else if (score >= 60) {
                grade = "D";
            } else if (score >= 50) {
                grade = "E";
            } else {
                grade = "F";
            }

            System.out.println("Grade: " + grade);
        } else {
            System.out.println("Invalid test score entered. Test score must be between 0 and 100.");
        }
    }
}


@@ Using Switch case

import java.util.Scanner;
public class GradeCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter your test score: ");
        int score = scanner.nextInt();

        if (score >= 0 && score <= 100) {
            String grade;

            switch (score / 10) {
                case 10:
                case 9:
                    grade = "A";
                    break;
                case 8:
                    grade = "B";
                    break;
                case 7:
                    grade = "C";
                    break;
                case 6:
                    grade = "D";
                    break;
                case 5:
                    grade = "E";
                    break;
                default:
                    grade = "F";
                    break;
            }

            System.out.println("Grade: " + grade);
        } else {
            System.out.println("Invalid test score entered. Test score must be between 0 and 100.");
        }
    }
}
