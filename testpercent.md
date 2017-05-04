# math-think
package com.company;
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        System.out.println("خط اول تعداد کل سوالات - خط دوم تعداد صحیح - خط سوم تعداد غلط");
        Scanner input=new Scanner(System.in);
        float b,h;
        int x,a,t,f,z;
        a=input.nextInt();
        t=input.nextInt();
        f=input.nextInt();
        x=t+f;
        z=a-x;
        b=(t*3)-f;
        h=a*3;
        h=b/h;
        h=h*100;
        System.out.println("تعداد نزده");
        System.out.println(z);
        System.out.printf("%3.2f",h);





    }
}
