# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
20219059

import java.util.Scanner;

public class Main {

    public static double temperatuur(double celsius) {
        double fahrenheit;
        return (fahrenheit = (celsius * 9 / 5.0) + 32);
    }
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double celsius = scanner.nextDouble();
        double fahrenheit = (temperatuur(celsius));
        System.out.printf("De temperatuur in Fahrenheit is: %.2f", fahrenheit);
    }
}