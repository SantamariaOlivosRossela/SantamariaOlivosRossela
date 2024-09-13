- 👋 Hi, I’m @SantamariaOlivosRossela
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
SantamariaOlivosRossela/SantamariaOlivosRossela is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


 */
package rossela;
import java.util.*;

/**
 *
 * @author LAB-USR-LNORTE
 */
public class ejercico3 {
      public static void main(String[] args) {
        Scanner lector = new Scanner(System.in);
        int compra;
        String cat;
          System.out.println("Ingrese la Categoria");
          cat=lector.netxLine();
                
          System.out.println("Ingresa tu compra para descuento: ");
        if (compra>= 25){
            
            System.out.println("Se aplica un 2% de descuento: ");
        }
        if (compra>= 25 && compra<=50){
            System.out.println("Se aplica un 3% de descuento: ");
        }
        if (compra>= 50 && compra<= 100){
            System.out.println("Se aplica un 5% de descuento: ");
        }
         if (compra>= 100 && compra<= 200){
            System.out.println("Se aplica un 10% de descuento: ");
         }
         if (compra>= 2000 ){
            System.out.println("Se aplica un 15% de descuento: ");
        }
         else {
             
        }

package rossela;
import java.util.*;

/**
 *
 * @author 
 */
public class Rossela {

    public static void main(String[] args) {
       Scanner lector = new Scanner(System.in);
       String operacion, creditoI,creditoT;
       int cafe;
       int credito=30;
       double costoI=3.50;
       double costoT=0.00;
       
        String menu= """
                     ************************************
                     Ingrese la operacion a realizar:
                     1.- Comprar café
                     2.- Agregar credito
                     3.- Consultar credito
                     ************************************                
                     """;
        System.out.printf(menu);
        
     String (operacion) {
    
            case 1: {
                System.out.println("Ingrese la cantidad de cafe que desea comprar, Cada cafe "
                        + "cuesta $3.50:");
                cafe=lector.netxInt();
                cafeT=costoI*cafe;
                creditoC=creditoT-cafeT;
                if (credito=0){
                System.out.println("Credito insuficiente para realizar esta operacion:");
    }
    }
            case 2: {
                System.out.println(" Agregue cuanto desea agregar al credito: ");
                credito=lector.nextLine();
                creditoT=creditoI+credito;
                
               System.out.printf("Credito disponible actual : %S", creditoT);
            case 3: {
               System.out.printf("Credito actual es: $ %S",credito);
               
 
           
               
    }   



      
