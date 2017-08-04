# MultiplicationTableGrid

import java.util.Scanner;

public class grid {


    public static void main(String[] args) {
        {

            Scanner keyboard = new Scanner(System.in);

            System.out.print("How large would you like to see them?");
            int size = keyboard.nextInt();

            for (int row = 0; row <= size; row++) {
                System.out.print("\t" + row);

            }
            System.out.println();

            for (int column = 0; column <= size; column++) {
                System.out.print(column);
                for (int row = 0; row <= size; row++) {
                    System.out.print("\t");
                    System.out.print(row * column);


                }
                System.out.println();


            }


        }
    }
}
