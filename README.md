package HomeWorkApp;

import javax.sql.rowset.serial.SQLOutputImpl;
import java.sql.SQLOutput;

public class FirstClass {

    public static void main(String[] args) {
        String PrintTreeWords;
        {
            System.out.println("Orange");
            System.out.println("Banana");
            System.out.println("Apple");
        }
        String checkSumSign;
        {
            int a = 5;
            int b = -6;
            if (a + b >= 0) {
                System.out.println("Сумма положительная");
            }
            else
            {
            System.out.println("Сумма отрицательная");
            }

        }
        String printColor;
        {
         int a = 101;
         if (a <= 0)
         {
             System.out.println("Красный");
         }
         else if (a > 0 && a <= 100)
         {
             System.out.println("Желтый");
         }
         else
         {
             System.out.println("Зеленый");
         }
        }
        String compareNumber;
        {
            int a = 7;
            int b = -9;
            if (a >= b)
            {
                System.out.println("a > b");
            }
            else
            {
                System.out.println("a < b");
        }
    }

}}

