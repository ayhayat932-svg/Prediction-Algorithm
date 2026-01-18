# Prediction-Algorithm
In this study, I developed a simple prototype of a guessing game algorithm.”

import java.util.Scanner;
public class tahmin {
    public static void main(String[] args) {

    int number = (int)(Math.random() *101);
    Scanner input = new Scanner(System.in);
    int guess = -1;

    while(guess != number) {
        System.out.println("Prodection : ");
        guess = input.nextInt();


        if (guess > number)
            System.out.println("Very high value");

        else if (guess < number)
            System.out.println("Very low value");



    }
        System.out.println("That's Rigth");
    }
