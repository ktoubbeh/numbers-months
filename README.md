# numbers-months



/*
 * Karen Toubbeh
 * Java
 * February 13, 2017
 *
 * Exercise #05
 */

import java.util.Scanner;

public class Months {
    public static void main(String[] args) {
    
    Scanner input = new Scanner(System.in);

    System.out.print("Enter a month as an integer (1-12): ");
    int month = input.nextInt();
    input.nextLine();

       if (month == 1)
                  System.out.println("January has 31 days");
            else if (month == 2)
                  System.out.println("February has 28 days");
            else if (month == 3)
                  System.out.println("March has 31 days");
            else if (month == 4)
                  System.out.println("April has 30 days");
            else if (month == 5)
                  System.out.println("May has 31 days");
            else if (month == 6)
                  System.out.println("June has 30 days");
            else if (month == 7)
                  System.out.println("July has 31 days");
            else if (month == 8)
                  System.out.println("August has 31 days");
            else if (month == 9)
                  System.out.println("September has 30 days");
            else if (month == 10)
                  System.out.println("October has 31 days");
            else if (month == 11)
                  System.out.println("November has 30 days");
            else if (month == 12)
                  System.out.println("December has 31 days");
            else
                  System.out.println("Not a month.");
                }
            }
/*
 * Karen Toubbeh
 * Java
 * February 13, 2017
 *
 * Exercise #05
 */

import java.util.Scanner;

public class Smallest
{
    public static void main(String[] args)
    {
        Scanner console = new Scanner (System.in);
    
        System.out.println("Enter three integers, I'll find the smallest:");
        
        int a = console.nextInt();
        int b = console.nextInt();
        int c = console.nextInt();
        
        
        
        System.out.println("The smallest is:");
        
        if (a < b) 
            System.out.println(a);
        else 
            System.out.println(b);
       
        
    }
}
        
        

