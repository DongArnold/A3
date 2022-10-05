# A3

import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	
		System.out.println("Enter First Number:");
		int n1 = sc.nextInt();
		
		System.out.println("Enter Second Number:" );
		int n2 = sc.nextInt();
		
		 int largest = n1;
	      if(largest < n2)
	      {largest=n2;}
	      
     System.out.println( largest +  " is larger" );
		
			
	}
}
