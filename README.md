package homwork2;

import java.util.Scanner;

public class test2 {

    public static void main(String[] args) {
Scanner n=new Scanner(System.in);
String q = "prime number" ;
        System.out.print("     Enter the number to find out whether or not it is a prime number = ");
        int num=n.nextInt();
        System.out.println("=============================================================================");
        if (num==1) {
            System.out.println("not prime number");
            
        }
        else {
        for (int x =2 ; x<num ; x++)
        {
   if (num%x==0){
  q= "not prime number" ;}
   
}
        System.out.println(q);
        
         System.out.println("=========================================================================");
        System.out.println("                              Good bay                                     ");
 
    }}
}
