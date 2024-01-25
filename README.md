*/  # Programaci-n-Java
     Repositorio para el curo de programación (Java)/*



     
package clase2;

import javax.swing.JOptionPane;

/**
 *
 * @author Aulas Heredia
 */
public class Clase2 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // repaso, 

       /* double miMesada = 100;
        double lunes = 10, martes = 11, miercoles = 20;
        System.out.println("Esto va para la consola");
        System.out.println("Mi dinero actual" + (miMesada - lunes - martes - miercoles));
        */
        
        
       // if (true){
     /*  int a=1;
       int b=1;
       if (a>=b || true){
            System.out.println("Entre en el if 1==1");
        }
        if (false){
            System.out.println("sssss");
        }*/
        String data = JOptionPane.showInputDialog("Ingrese su del curso anterior ");
        JOptionPane.showMessageDialog(null, data);
        int nota;
        nota = Integer.parseInt(data);
        if (nota >= 70) {
            JOptionPane.showMessageDialog(null, "Aprobo");
        } else {
            JOptionPane.showMessageDialog(null, "No Aprobo");
        }
        String data2 = JOptionPane.showInputDialog("Ingrese su nota final del curso");
        JOptionPane.showMessageDialog(null, data2);
        int nota2;
        nota2 = Integer.parseInt(data2);

        if (nota2 >= 70) {
            JOptionPane.showMessageDialog(null, "Aprobo");
        } else {
            JOptionPane.showMessageDialog(null, "No Aprobo");
        }
        
       /* if (edad > 30) {
            JOptionPane.showMessageDialog(null, "El puede ser presidente ");
        } else {
            JOptionPane.showMessageDialog(null, "El no puede ser presidente ");
        }*/
       
      /*  int var = 2;
        switch (var) {
            case 1:
                System.out.println("Es Lunes");
                break;
            case 2:
                System.out.println("Es Martes");
                 break;
            case 3:
                System.out.println("Es Miercoles");
                 break;
            case 4:
                System.out.println("Es Jueves");
                 break;
            case 5:
                System.out.println("Es Viernes");
                 break;
        }*/
    }
}


parte 2 

  int dia = 5;
        switch (dia) {
            case 1:
                System.out.println("Es Domingo");
                break;
            case 2:
                System.out.println("Es Lunes");
                break;
            case 3:
                System.out.println("Es Martes");
                break;
            case 4:
                System.out.println("Es Miercoles");
                break;
            case 5:
                System.out.println("Es Jueves");
                break;
            case 6:
                System.out.println("Es Viernes");
                break;
            case 7:
                System.out.println("Es Sabado");
                break;
