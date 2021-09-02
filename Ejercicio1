# Diagnostico
package diagnostico;
import java.util.Scanner;
/**
 *
 * @author Elier
 */
public class Ejercicio1 {
    public static void main(String[] args) {

        Scanner teclado=new Scanner(System.in);
        
        System.out.println("Ingresa el tamaño de la matriz:"); 
        int n=teclado.nextInt();

        if (n == 0)
            System.out.println("No se puede mostrar la matriz");
        else {
            String[][]dibujo = new String[n][n];

            for ( int i=0; i < dibujo.length ;i++){
                for (int j=0;  j<dibujo.length;j++){
                    int x = i +1;
                    if((i==j)  ||  (j == (n - x))){
                        dibujo[i][j] = "*";
                        System.out.print(dibujo[i][j] + " ");
                    }
                    else{
                       dibujo[i][j] = " ";
                       System.out.print(dibujo[i][j] + " ");
                    }
                }  
                System.out.println();
            }   
        }
    }
}
