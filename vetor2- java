import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		
		int N = sc.nextInt();
		int[] vet = new int[N];
		
		for(int i=0; i<N; i++) {
			vet[i] = sc.nextInt();
		}
		
		for(int i=0; i<N; i++) {
			if(vet[i] % 2 == 0) {
				System.out.print(vet[i] + " ");
			}
		}
		System.out.println();
		
		int quantPares = 0;
		for(int i=0; i<N; i++) {
			if(vet[i] % 2 == 0) {
				quantPares++;
			}
		}
		
		System.out.println(quantPares);
		
		sc.close();
	}

}
