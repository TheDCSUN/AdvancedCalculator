import java.util.Scanner;//importing Scanner class
public class Calculator_Switch {
	public static int sum(int a,int b)//Function for addition
	{
		return a+b;
	}
	public static int diff(int a,int b)//Function for subtraction
	{
		return a-b;
	}
	public static int multiply(int a,int b)//Function for multiplication
	{
		return a*b;
	}
	public static double divide(double a,double b)//Function for division
	{
		return a/b;
	}
	public static double exponent(double a,double b)//Function for exponential calculations
	{
		return Math.pow(a, b);
	}
	public static double sin(double deg)//Function for sine 
	{
		double rad = Math.toRadians(deg);
		double s = Math.sin(rad);
		return s;
	}
	public static double cos(double deg)//Function for cosine
	{
		double rad = Math.toRadians(deg);
		double c = Math.cos(rad);
		return c;
	}
	public static double tan(double deg)//Function for tangent
	{
		double rad = Math.toRadians(deg);
		double t = Math.tan(rad);
		return t;
	}
	public static void main(String[] args) {

		while(true)//To keep the program running till the user wants to stop it
		{
			Scanner sc = new Scanner(System.in);
			System.out.println("Enter your choice : +,-,*,/,^,s(sin),c(cos),t(tan)");//Displays all the available options
			char choice = sc.next().charAt(0);
			switch(choice)
			{
			case '+': 
			{
				System.out.println("Enter the value of 'a'");
				int a = sc.nextInt();
				System.out.println("Enter the value of 'b'");
				int b = sc.nextInt();
				System.out.println("The sum is = "+sum(a,b));//Sum
			}
			break;
			case '-': 
			{
				System.out.println("Enter the value of 'a'");
				int a = sc.nextInt();
				System.out.println("Enter the value of 'b'");
				int b = sc.nextInt();
				System.out.println("The difference is = "+diff(a,b));//Difference
			}
			break;
			case '*': 
			{
				System.out.println("Enter the value of 'a'");
				int a = sc.nextInt();
				System.out.println("Enter the value of 'b'");
				int b = sc.nextInt();
				System.out.println("The product is = "+multiply(a,b));//Product
			}
			break;
			case '/': 
			{
				System.out.println("Enter the value of 'a'");
				double a = sc.nextDouble();
				System.out.println("Enter the value of 'b'");
				double b = sc.nextDouble();
				System.out.println("The quotient is = "+divide(a,b));//Quotient
			}
			break;
			case '^': 
			{
				System.out.println("Enter the value of 'a'");
				double a = sc.nextDouble();
				System.out.println("Enter the value of 'b'");
				double b = sc.nextDouble();
				System.out.println("The exponential value is = "+exponent(a,b));//Exponential value
			}
			break;
			case 's':
			{
				System.out.println("Enter the value of the angle in degrees(without symbol)");
				double deg = sc.nextInt();
				System.out.println("The sin of "+deg+" degrees is = "+sin(deg));//Sine 
			}
			break;
			case 'c':
			{
				System.out.println("Enter the value of the angle in degrees(without symbol)");
				double deg = sc.nextInt();
				System.out.println("The cos of "+deg+" degrees is = "+cos(deg));//Cosine
			}
			break;
			case 't':
			{
				System.out.println("Enter the value of the angle in degrees(without symbol)");
				double deg = sc.nextInt();
				System.out.println("The tan of "+deg+" degrees is = "+tan(deg));//Tangent
			}
			break;
			default:
				System.out.println("Wrong symbol!");
			}

			
			System.out.println("To continue press any key, otherwise press 0");//Asks for User's choice
			int p = sc.nextInt();
			if(p==0)
			{
				System.exit(0);
			}
			else 
			{
				continue;
			}
			sc.close();
		}
	}

}
