import java.util.Scanner; 
//imports the scanner classpublic class Calculator {
//main method begins execution of java programpublic static void main( String[]args){
//Create a Scanner to input information	Scanner 
input = new Scanner(System.in);	
//Declaring the variables	
int Number1;	
int Number2;
int Output;	
String operation;	
System.out.print("Enter the Frist digit: ");
Number1 = input.nextInt();
//Stores the input from user to number1 variable	
System.out.print("Enter the Second digit: ");
Number2 = input.nextInt();
System.out.println("Please enter the operation: \n(+, -, *, /, %) ");
operation = input.next();
if (operation.equals( "+"))	{	
Output= Number1 + Number2;		
System.out.printf("The Addition of %d + %d = %d\n", Number1, Number2, Output);
}	else 
if (operation.equals( "-"))		{	
Output = Number1 - Number2;	
System.out.printf("The Subtraction of %d - %d = %d\n", Number1, Number2, Output);	
}	else 
if (operation.equals( "/"))			{	
Output = Number1 / Number2;	
System.out.printf("The Division of %d / %d = %d\n", Number1, Number2, Output);	
}	else if (operation.equals( "*"))			
{				
Output = Number1 * Number2;	
System.out.printf("The Multiplication of %d x %d = %d\n", Number1, Number2, Output);	
}	
else 
if (operation.equals( "%"))				
{							
Output= Number1 % Number2;	

System.out.printf("The Remainder of %d Mod %d = %d\n", Number1, Number2, Output);				
}	
else	
System.out.println("Wrong operator entered");}
//End method main}
//End class 
