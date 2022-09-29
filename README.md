import java.util.Scanner;

public class Exemplo3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	Scanner ser = new Scanner (System.in);
	int x;
	int v;
	
	System.out.println("Digite o valor 1 : " );
	x = ser.nextInt();
	System.out.println("Digite o valor 2 : " );
	v = ser.nextInt();
	
	if (x % v == 0 || v % x == 0){
		
	System.out.println("Numeros multiplos entre si ");
	}
    
	else {
		System.out.println("Numeros nao multiplos");
	    }
	   ser.close();
	}

}
