# GreaterAndLower
Using this code compare two Int values
package mypackage;
import java.util.Scanner;
public class {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
  System.out.print("Enter first Number:");
    int n=sc.nextInt();
    System.out.print("Enter Second Number:");
    int m=sc.nextInt();
    if(n<m) {
    	System.out.print("second is Greater :");
    }else if(n==m) {
    	System.out.print("Both are equel:");
    	
    }else {
    	System.out.print("first is Greater:");
    }
	}

	}
