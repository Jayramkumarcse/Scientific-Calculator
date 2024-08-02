package Java;
import java.util.Scanner;
public class Calculator {
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		int res=0;
		System.out.println("Enter the First Number:");
		int n1=s.nextInt();
		System.out.println("Enter the Second Number:");
		int n2=s.nextInt();
		System.out.println("1.Addition");
		System.out.println("2.Subtraction");
		System.out.println("3.Multiplication");
		System.out.println("4.Division");
		System.out.println("Enter your Choice:");
		int ch=s.nextInt();
		switch (ch)
		{
		case 1:res= n1+n2;//10
		case 2:res=n1-n2;//5
		case 3:res=n1*n2;break;
		case 4:res=n1%n2;break;
		default:
			System.out.println("Invalid Your Choice:"); System.exit(1);//comes of programs
		}
		System.out.println("Result="+res);
	}

}
