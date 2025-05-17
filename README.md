# desafio10
# quesato 1
```java
package desafio;

/**
 * 1. Criar dois vetores A e B cada um com 10 elementos inteiros. Construir um
 * vetor C, onde cada elemento de C é a soma dos respectivos elementos em A e B,
 * ou seja: C[i] = A[i] + B[i].
 *
 * @author Henrique
 */
public class Desafio {

    public static void main(String[] args) {
        int[] a = {20, 19, 17, 18, 13, 5, 4, 2, 31, 7};
        int[] b = {71, 70, 59, 55, 54, 36, 28, 25, 17, 9};
        int[] c = new int[10];
        for (int i = 0; i < a.length; i++) {
            c[i] = a[i] + b[i];
            System.out.println(a[i] + " + " + b[i] + " = " + c[i]);
        }
    }

}
```
# questao 2
```java
package desafio;

/**
 * 2. Criar dois vetores A e B cada um com 10 elementos inteiros. Construir um
 * vetor C, onde cada elemento de C é a subtração dos respectivos elementos em A
 * e B, ou seja: C[i] = A[i] – B[i].
 *
 * @author Henrique
 */
public class Desafio {

    public static void main(String[] args) {
        int[] a = {20, 19, 17, 18, 13, 5, 4, 2, 31, 7};
        int[] b = {71, 70, 59, 55, 54, 36, 28, 25, 17, 9};
        int[] c = new int[10];
        for (int i = 0; i < a.length; i++) {
            c[i] = a[i] - b[i];
            System.out.println(a[i] + " - " + b[i] + " = " + c[i]);
        }
    }

}
```
# questao 3
```java
package desafio10;

import java.util.Scanner;

/**
 * 3. Crie um programa que leia um vetor de 10 elementos de números inteiros e
 * exiba na tela o valor máximo e o valor mínimo contido no vetor.
 *
 * @author Henrique
 */
public class Desafio10 {

    public static void main(String[] args) {
        int[] elementos = new int[10];
        Scanner ler = new Scanner(System.in);
        int max = elementos[0];
        int min = elementos[0];

        for (int i = 0; i < elementos.length; i++) {
            System.out.println("Digite um número:");
            elementos[i] = ler.nextInt();

            if (elementos[i] > max) {
                max = elementos[i];
            } else if (elementos[i] < min) {
                min = elementos[i];
            }
        }
        System.out.println("\nMaior valor:" + max);
        System.out.println("Menor valor:" + min);

    }
}
```
# questao 4
```java
package desafio10;

import java.util.Scanner;

/**
 * 4. Crie um programa que leia um vetor de 10 elementos de números inteiros e
 * exiba na tela apenas os números pares contidos no vetor.
 *
 * @author Henrique
 */
public class Desafio10 {

    public static void main(String[] args) {
        int[] n = new int[10];
        Scanner ler = new Scanner(System.in);

        for (int i = 0; i < n.length; i++) {
            System.out.println("Digite um numero:");
            n[i] = ler.nextInt();
        }
        System.out.println("\nOs numeros pares digitados:");
        for (int i = 0; i < n.length; i++) {
            if (n[i] % 2 == 0) {
                System.out.println(n[i]);
            }
        }

    }
}
```
# questao 5
```java
package desafio10;

import java.util.Scanner;

/**
 * 5. Crie um programa que leia um vetor de 10 elementos de números inteiros e
 * exiba na tela apenas os números ímpares contidos no vetor.
 *
 * @author Henrique
 */
public class Desafio10 {

    public static void main(String[] args) {
        int[] n = new int[10];
        Scanner ler = new Scanner(System.in);

        for (int i = 0; i < n.length; i++) {
            System.out.println("Digite um numero:");
            n[i] = ler.nextInt();
        }
        System.out.println("\nOs numeros impares digitados:");
        for (int i = 0; i < n.length; i++) {
            if (n[i] % 2 != 0) {
                System.out.println(n[i]);
            }
        }

    }
}
```
# questao 6
```java
package desafio10;

import java.util.Scanner;

/**
 * 6. Crie um programa que leia um vetor de 10 elementos de números inteiros e
 * calcule a média dos valores presentes nas posições pares do vetor.
 *
 * @author Henrique
 */
public class Desafio10 {

    public static void main(String[] args) {
        int[] n = new int[10];
        Scanner ler = new Scanner(System.in);
        int soma = 0, c = 0;

        for (int i = 0; i < n.length; i++) {
            System.out.println("Digite um numero:");
            n[i] = ler.nextInt();
            if (i % 2 == 0) {
                soma += n[i];
                c++;
            }
        }

        double media = (double) soma / c;
        System.out.println("\nMedia dos numeros pares é:" + media);

    }
}
```
