# Pr-ctica-
//programa de suma que utiliza a JOptionPane para entrada y salida
import javax.swing.JOptionPane;

public class Suma
{
public static void main(String args[])
   {
        // obtiene la entrada del usuario de los dialogos de JOptionPane
         String primerNumero =
         JOptionPane.showImputDialog ("introduzca el numero entero");
         String segundoNumero =
         JOptionPane.showImputDialog ("introduzca el numero entero");
         
        //convierte la entrada String en valores int para usarlos en el calculo    
   int numero1 = Integer.paraseInt(primer numero);
   int numero2 = Integer.paraseInt(segundo numero);
        
   int suma = numero1 + numero2; //se suman los numeros
        
        // muestra los resultados en un dialogo de mensajes de JOptionPane
   JOptionPane.showImputDialog ( null "la suma es" + suma, "suma de dos enteros", JOptionPane.PLAIN_MASSAGE);
   
  }//fin del metodo main
}//fin de la clase Suma
