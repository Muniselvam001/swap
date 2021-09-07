# swapimport java.util.Scanner;
public class Swap{

  public static void main(String[]args) 
   {
     int x=2,y=3;

     System.out.println("before swap");
     System.out.println("x="+x);
     System.out.println("y="+y);

     int temp=x;
     x=y;
     y=temp;

     System.out.println("after swap");
     System.out.println("x="+x);
     System.out.println("y="+y);
    }
   }
