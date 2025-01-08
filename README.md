# calculo media em java

package calculo;

import java.util.Scanner;

public class Media {
	
	public static void main(String [] args) {
		
		double r1 = 0;
		double r2 = 0;
		
		Scanner ler = new Scanner(System.in);
		
		System.out.println("Digite o primeiro número: " );
		
		r1 = ler.nextDouble();
		
		System.out.println("Digite o segundo número: " );
		
		r2 = ler.nextDouble();

		
		double media_total = (r1 + r2)/2 ;
		
		System.out.printf("O resultado da media é %f: ", media_total);	
		
	}	
		
		
}
