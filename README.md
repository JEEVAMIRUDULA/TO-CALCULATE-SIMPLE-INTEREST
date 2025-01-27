# TO-CALCULATE-SIMPLE-INTEREST
package smpleinterest;
import java.util.Scanner;
public class SmpleInterest {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the principal amount :");
        double principal = sc.nextDouble();
        System.out.println("Enter the rate of interest (in percentage):");
        double rate=sc.nextDouble();
        System.out.println("Enter the time period (in years):");
        double time = sc.nextDouble();
        double simple_interest =(principal*rate*time)/100;
        System.out.println("The simple interest is :" + simple_interest);
                
    }
    
}

O/P
Enter the principal amount :
20000
Enter the rate of interest (in percentage):
5
Enter the time period (in years):
2
The simple interest is :2000.0
BUILD SUCCESSFUL (total time: 23 seconds)

