import java.util.Scanner;
public class BiggestNumber
{
 public static void main(String[]args)
  {
    int x,y,z;
    Scanner s=new Scanner(System.in);
    System.out.print("enter the first number:");
    x=s.nextInt();
    System.out.print("enter the second number:");
    y=s.nextInt();
    System.out.print("enter the third number:");
    z=s.nextInt();
    if(x>y&&x>z)
    {
      System.out.println("Largest number is:"+x);
    }
    else if(y>x&&y>z)
     {
      System.out.println("Largest number is:"+y);
     }
     else
     {
      System.out.println("Largest number is:"+z);
     }
 
    }
   } 
