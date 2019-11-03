# pattern4

import java.util.Scanner;
public class pattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
        Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		int k=1;
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				System.out.print((char)(k+96) + " ");
				k++;
			}
			System.out.println();
		}
	}

}

output ::

5                                when n is 5
a 
b c 
d e f 
g h i j 
k l m n o 
