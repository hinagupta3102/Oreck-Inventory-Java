# Oreck-Inventory-Java
Oreck Inventory Calculation Program in Java
package inventory;

import java.util.Scanner;


public class Inventory {

    
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter the number that the inventory says right now");
        int Current = input.nextInt();
        System.out.println("Enter the number you want it to say");
        int Final = input.nextInt();
        System.out.println("Enter this number in inventory adjust, " + (Current - Final));
       }
    

}
