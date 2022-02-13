import java.util.Scanner;     //Allows scanner to be used

public class DogCalc {
   public static void main(String [] args) {
      Scanner scnr = new Scanner(System.in);     //Creating a scanner object to read keyboard input
      int dogYears;     //Initializing dog years and human years as integers
      int humanYears;

      dogYears = scnr.nextInt();     //Assigns the next keyboard integer input to be the value for dog years
      
      if (dogYears <= 0) {     //If-else statement that covers all possibilities for dog age
	      humanYears = 0;
	      System.out.print("A " + dogYears + " year old dog is about a " + humanYears + " year old human.");   //Concatenated final statement output
	    } else if (dogYears == 1) {
	      humanYears = 15;
	      System.out.print("A " + dogYears + " year old dog is about a " + humanYears + " year old human.");
	    } else if (dogYears == 2) {
	      humanYears = 15 + 9;
	      System.out.print("A " + dogYears + " year old dog is about a " + humanYears + " year old human.");
	    } else if (dogYears > 2) {
	      humanYears = (dogYears * 5) + 24;
	    } else {
	      System.out.println("Error, please retry");     //Error message that displays as a last resort, just in case
	    }

   }
}
