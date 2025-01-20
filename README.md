# Simple-interest-
public class SIMPLEINTREST {

/**

* @param args the command line arguments

*/

public static void main (String args[]) {

double principal, rate, time, simple_interest;

Scanner my_scanner = new Scanner(System.in);

System.out.println("Enter a Principal amount : ");

principal = my_scanner.nextDouble();

System.out.println("Enter an Interest rate : ");

rate = my_scanner.nextDouble();

System.out.println("Enter a Time period in years : ");

time = my_scanner.nextDouble();

simple_interest = (principal * rate * time) / 100;

System.out.println("The Simple Interest is : " + simple_interest);

double totalSum = simple_interest + principal;

System.out.println("Your total sum after gaining interest : " + totalSum);

}

}
OUTPUT

Enter a Principal amount :

2500

Enter an Interest rate :

3

Enter a Time period in years :

2

The Simple Interest is : 150.0

Your total sum after gaining interest : 2650.0
