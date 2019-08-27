import java.util.Scanner;
public class Teste {
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
    double kid = 0;
    double kid1 = 0;
    double sai = 0;
    int kod;
    Scanner s = new Scanner(System.in);
    System.out.println("Bem vindo a Reimagined Calc! Java Edition. Escolha a operação matemática:"
    		+ " (1)Soma"
    		+ " (2)Subtração"
    		+ " (3)Divisão"
    		+ " (4)Multiplicação");
    kod = s.nextInt();
    
    switch(kod) {
    
    case 1:
    	System.out.println("Insira os valores para a soma.");
    	kid = s.nextDouble();
    	kid1 = s.nextDouble();
    	sai = kid + kid1;
    	System.out.println("O resultado da operação é " + sai);
    	break;
    	
    case 2:
    	System.out.println("Insira os valores para a subtração.");
    	kid = s.nextDouble();
    	kid1 = s.nextDouble();
    	sai = kid - kid1;
    	System.out.println("O resultado da operação é " + sai);
    	break;
    
    case 3:
    	  int kud;
    	System.out.println("Escolha dois valores.");
          kid = s.nextDouble();
          kid1 = s.nextDouble();
          System.out.println("Opção (1) - Dividir " + kid + " por " + kid1);
          System.out.println("Opção (2) - Dividir " + kid1 + " por " + kid);
           kud = s.nextInt();
           switch(kud) {
           case 1:
        	   sai = kid/kid1;
               System.out.println("O resultado da operação é " + sai);
        	   break;
           case 2:
        	   sai = kid1/kid;
               System.out.println("O resultado da operação é " + sai);
        	   break;
           }
    	break;
    	
    case 4:
    	System.out.println("Insira os valores para a multiplicação.");
    	kid = s.nextDouble();
    	kid1 = s.nextDouble();
    	sai = kid * kid1;
    	System.out.println("O resultado da operação é " + sai);
    	break;
    	
    
    }
    
	}
	
}
