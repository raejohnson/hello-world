/* package whatever; // don't place package name! */

import java.util.scanner;


/* Name of the class has to be "Main" only if the class is public. */
public class SalesFunction
{
	public static void main (String[] args); 
	Scanner keyboard= new Scanner(System.in);
	{
		String amount;
		
		double salesTax;
		double totalsalesTax;
		double totalSaleAmount;
		
		System.out.println("Please enter your purchase amount : ");
		amount= keyboard.nextLine();
		
		salesTax= .07;
		
		totalStateTax = amount * stateTax;
		totalSaleAmount = amount + totalSalesTax;
		
		System.out.print("The purchase amount is " + amount + '\n');
		System.out.print("The state sales tax is " + salesTax + '\n');
		System.out.print("The total sales tax is " + totalSalesTax + '\n');
		System.out.println("The total amount of the sales is " +totalSalesAmount+ '\n');
		
	}
}
