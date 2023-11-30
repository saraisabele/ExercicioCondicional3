# ExercicioCondicional3
# programa que descobre se dois números inteiros inseridos pelo usuário são múltiplos ou não 

package exercicioCond3;
import java.util.Scanner;

public class MultiplosOuNao {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in); 
		System.out.printf("Digite um número inteiro: ");
		int numeroInteiro1 = sc.nextInt();
		System.out.printf("Digite mais um número inteiro: ");
		int numeroInteiro2 = sc.nextInt();
		
		if (numeroInteiro1 % numeroInteiro2 == 0 || numeroInteiro2 % numeroInteiro1 == 0) {
		System.out.printf("%d e %d são múltiplos", numeroInteiro1 , numeroInteiro2);
		}
		else {
			System.out.printf("%d e %d não são múltiplos", numeroInteiro1 , numeroInteiro2);
		}
		
		sc.close();
		}
		
	}
	
