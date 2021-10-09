import java.util.Scanner;

public class Main {

  public static void main(String[] args) {

/* this is a pytagoras theoremy. 
I will define the sides with double, because is not a int number */

    double FirstCatet;

    double SecondCatet;

    double Hypotenusa; 

/* Scanner for define a new variable */

    Scanner scanner = new Scanner(System.in);

    System.out.println("Enter the first side");

    FirstCatet = scanner.nextDouble();
    System.out.println("Enter the second side");

    SecondCatet = scanner.nextDouble();

    Hypotenusa = Math.sqrt((FirstCatet*FirstCatet)+
    (SecondCatet*SecondCatet));

    System.out.println("The hypotenuse is : "+Hypotenusa);
    
    scanner.close();

  }
}
