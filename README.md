# 5-ways-of-swapping-a-number
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    System.out.print("Enter the first number: ");
	    int a =sc.nextInt();
	    System.out.print("Enter the second number: ");
	      int b = sc.nextInt();
	    System.out.println("Before swapping a number"+a+" "+b);
		a = a+b;
		b = a-b;
		a = a-b;
		System.out.println("After swapping a number"+a+" "+b);
	}
}
