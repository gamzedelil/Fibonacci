# Fibonacci

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
  
     int n;
     System.out.println("Istediginiz eleman sayisini girin:");
     n = input.nextInt();
        
     int a = 0;
     int b = 1;

        for (int i=0; i<=n; i++){	
        	System.out.println(a+ "");
      
        	int temp = a;
        	a = b;
        	b = temp + b;
    }    
  }	 
}
		
