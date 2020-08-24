# encryption-of-char


import java.util.*;
import java.io.*;

public class HelloWorld
{
     public static void main(String []args)
     {
        Scanner sc=new Scanner(System.in);
        char ch=sc.next().charAt(0);
        int a=ch;
        int b=sc.nextInt();
        int p=a+b;
        if(a>64 && a<91)
        {
            while(p>90)
            {
                p=p-26;
            }
        }
        else
        {
            while(p>122)
            {
                p=p-26;
            }
        }
        char j=(char)p;
        System.out.print(j);
     }
}
