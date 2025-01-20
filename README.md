import java.util.Scanner;  //Aqui é a importação da função que Ler as entradas

public class CalculadoraResistencias {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in); // Aqui você faz a funcionalidade

        System.out.print("Digite o valor de R1: ");
        double r1 = scanner.nextDouble(); // Aqui é usado o scanner.next, precisa aprender isso.

        System.out.print("Digite o valor de R2: ");
        double r2 = scanner.nextDouble();

        System.out.print("Digite o valor de R3: ");
        double r3 = scanner.nextDouble();

        System.out.print("Digite o valor de R4: ");
        double r4 = scanner.nextDouble();

        double somaResistencias = r1 + r2 + r3 + r4;

// Pra fazer mais rápido a digitação do print é só colocar Souto e tab
        System.out.println("A soma das resistências é: " + somaResistencias);
    }
}
