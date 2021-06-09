# package-
solving printing full name on scanner

import java.util.Scanner;

public class Print {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println(" Enter your full name ");
        System.out.println("Enter your fist name =");
        String name1= sc.nextLine();
        System.out.println("Enter your Seconed name =");
        String name2=sc.nextLine();
        String sum =name1+name2;
        System.out.println("your full Names is ="+sum);
    }
}
