import java.util.Scanner;

public class Calculadora {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        char continuar = 'S';
        
        while (continuar == 'S') {
            System.out.println("Digite o primeiro número: ");
            double num1 = sc.nextDouble();
            
            System.out.println("Digite o segundo número: ");
            double num2 = sc.nextDouble();
            
            System.out.println("Digite a operação que deseja realizar (+,-,*,/): ");
            char operacao = sc.next().charAt(0);
            
            double resultado = 0;
            switch (operacao) {
                case '+':
                    resultado = num1 + num2;
                    break;
                case '-':
                    resultado = num1 - num2;
                    break;
                case '*':
                    resultado = num1 * num2;
                    break;
                case '/':
                    resultado = num1 / num2;
                    break;
                default:
                    System.out.println("Operação inválida!");
                    break;
            }
            
            System.out.println("O resultado da operação é: " + resultado);
            System.out.println("Deseja continuar? (S/N)");
            continuar = sc.next().charAt(0);
        }
        
        System.out.println("Programa encerrado.");
    }
}
