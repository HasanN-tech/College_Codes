import com.sun.glass.ui.Size;

import java.lang.reflect.Array;
import java.util.Scanner;
import java.util.*;
public class Main {
    public static void main(String[] args) {
        /*int x = 5;
        for (int i = 0; i < x; i++) {
            for (int j = 0; j < x; j++)
                System.out.print("*");
            System.out.println();
        }*/
        Scanner sc = new Scanner(System.in);
      //  System.out.println("Enter any amount");
        /*int y= sc.nextInt();
        if (y%2==0)
            System.out.println(y+" is even");
        else System.out.println(y+" is odd");*/
        /*int z = sc.nextInt();
        for (int i = z; i > 0; i--) {
            for (int j = 1; j <i; j++)
                System.out.print(" ");
            for (int k=i-1;k<z;k++)
                System.out.print("*");
            System.out.println();
        }*/
       /* int a = sc.nextInt();
        for (int i = 0; i < a; i++) {
            for (int j = 0; j < i+1; j++)
                System.out.print("*");
            System.out.println();
        }
        for (int i = a-1; i>0; i--) {
            for (int j = 0; j < i; j++)
                System.out.print("*");
            System.out.println();
        }*/
        /*int a=sc.nextInt();
        System.out.println("Entered amount is "+a);
        System.out.println("500 rupees notes "+a/500);
        System.out.println("100 rupees notes "+(a%500)/100);
        System.out.println("50 rupees notes "+((a%500)%100)/50);
        System.out.println("20 rupees notes "+(((a%500)%100)%50)/20);
        System.out.println("10 rupees notes "+((((a%500)%100)%50)%20)/10);
        System.out.println("2 rupees notes "+(((((a%500)%100)%50)%20)%10)/2);
        System.out.println("1 rupees notes "+((((((a%500)%100)%50)%20)%10)%2)/1);*/

        /*int[] array = new int[10];
        System.out.println("Enter 10 values-");
        for (int i=0;i<10;i++){
            array[i]=sc.nextInt();
        }
        for (int i = 0, j = array.length - 1; i < j; i++, j--) {
            int temp = array[i];
            array[i] = array[j];
            array[j] = temp;
        }
        for (int i = 0; i < array.length; i++) {
            System.out.print(array[i]+" ");
        }*/
       /* System.out.println("Enter any number:-");
        int number= sc.nextInt();*/
       /* boolean isprime=true;
        for (int i=2;i<number;i++)
            if (number%i==0){
                isprime=false;
                break;
            }
        if (isprime==true)
            System.out.println("Number is Prime");
        else System.out.println("Number is not Prime");*/

        /*int num2= sc.nextInt();
        number=number+num2;
        num2=number-num2;
        number=number-num2;
        System.out.println("Numbers after swapping -"+number+" / "+num2);*/
        /*float c=(number-32)*5/9;
        System.out.println("Fahrenheit = "+number);
        System.out.println("Celcius = "+c);*/

        /*System.out.println("Size of char = "+ Character.SIZE+" byte");
        System.out.println("Size of char = "+ Integer.SIZE+" byte");
        System.out.println("Size of char = "+ Float.SIZE+" byte");
        System.out.println("Size of char = "+ Double.SIZE+" byte");
        int n=5;
        for (int i=0;i<n;i++){
            for (int j=0;j<n;j++)
                if (i==0 || j==0 || i==n-1 || j==n-1)
                    System.out.print("* ");
                else System.out.print("  ");
                System.out.println();
        }
        System.out.println("---------------------------------------");
        for (int i=1;i<=n;i++){
            for (int j=1;j<=i;j++)
                System.out.print(j+" ");
            System.out.println();
        }*/
        System.out.println("Enter 10 values:");
        int[] arr = new int[10];
        for (int i=0;i<arr.length;i++)
            arr[i]= sc.nextInt();
        System.out.println("Minimum value : "+Arrays.stream(arr).min().getAsInt());
        System.out.println("Maximum value : "+Arrays.stream(arr).max().getAsInt());
    }
}
