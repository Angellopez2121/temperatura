# temperatura
package temperatura;
import java.util.*;

public class Temperatura {


    public static void main(String[] args) {
Scanner sc= new Scanner(System.in);
int a;
        System.out.println("Escribe el grado de temperatura");
        a=sc.nextInt();
      if (a<=10)  
            System.out.println("La temperatura es de frio");
      else if (a>10&&a<=20)     
            System.out.println("La temperatura es Nubloso");
      else if (a>20&&a<=30)
            System.out.println("La temperatura es caluroso");
      else if (a>30)
            System.out.println("La temperatura es tropical");
      
    }  
}
