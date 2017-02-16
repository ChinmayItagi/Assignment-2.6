//1) Write a program to accepts two numbers from stdin and find all the odd as well as even
//numbers present in between them.

import java.util.Scanner;

public class Main {
	
public static void main(String args[])
{
		StringBuffer sb = new StringBuffer();
		StringBuffer sb1 = new StringBuffer();
		Scanner sc =new Scanner(System.in);
		int a = sc.nextInt();
		int b =sc.nextInt();
		for (int i = a; i <=b; i++) {
			if(i%2==0)
			{
				sb.append(i);
				sb.append(" ");
			}
			else
			{
				sb1.append(i);
				sb1.append(" ");
			}
		}
		System.out.println("Output");
		System.out.println("even");
		System.out.println(sb.toString());
		System.out.println("odd");
		System.out.println(sb1.toString());
	}

}



//3) Write a program consisting method sum() and demonstrate the concept of method
//overloading using this method.


import java.util.Scanner;

public class Main {
	
public static void main(String args[])
	{
		Scanner sc= new Scanner(System.in);
		System.out.println("Enter the number");
		int a = sc.nextInt();
		
		for (int i = 1; i <=10; i++) {
			System.out.println(i*a);
			
		}
	}

}

//3) Write a program consisting method sum() and demonstrate the concept of method
//overloading using this method.


import java.util.Scanner;

public class Main {
	public static int sum(int a , int b)
    {
         
         return a+b;
    }
    public static String  sum(String s ,String s1)  
    {
    	String s4 = s+s1;
        return s4;
    }
	
	public static void main(String args[])
	{
		Scanner sc= new Scanner(System.in);
		
		int a = sc.nextInt();
		int b = sc.nextInt();
		String s = sc.next();
		String s4 = sc.next();
		System.out.println("Output");
		System.out.println(sum(a,b));
		System.out.println(sum(s,s4));
		}
	}
  

