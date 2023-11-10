# WhileDC
WhileDC

package exemplos;

import java.util.Scanner;

public class ExemploWhileDC {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int x=0,r=0;
		String resp;
		
		resp="sim";
		
		while(resp.equals("sim")) {
			System.out.println("Digite um numero: ");
			x=sc.nextInt();
			r=x*3;
			System.out.println("A resposta multiplição é :" + r);
			System.out.println("Deseja efetuar outra operação? : ");
			//sc.next(resp);// conceito de  parametro 
			resp=sc.next();
			
		}
		sc.close();

	}

}

