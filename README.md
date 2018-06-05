# practicaentonos

import java.util.Scanner;
public class ejercicio2
{
    public static void main(String[] args)
    {
      Scanner leer=new Scanner(System.in);
      int tam;
      int array[];
      do{
      System.out.print("Dame el tamaño del array: ");
      tam=leer.nextInt();
    }while(tam<0);
    array=new int [tam];
    System.out.print("Dame los datos del array: ");
    for(int ind=0; ind<array.length; ind ++)
    {
        array[ind]=leer.nextInt();
    }
    for(int ind=0; ind<array.length; ind ++)
    {
        System.out.println("El array es: "+array[ind]);
    } 
}
