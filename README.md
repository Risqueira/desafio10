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
