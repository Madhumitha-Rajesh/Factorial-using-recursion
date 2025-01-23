# Factorial-using-recursion

CODING-

package factoriall;
import java.util.Scanner;

public class Factoriall {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc=new Scanner(System.in);
        int num;
        System.out.println("enter the number:");
        num=sc.nextInt();
        long factorial = multiplyNumbers(num);
        System.out.println("Factorial of " + num + " = " + factorial); 
    }
    public static long multiplyNumbers(int num){
        if(num>=1){
            return num*multiplyNumbers(num-1);
        
        }
        else
            return 1;
    }

}


Output-

enter the number:
4
Factorial of 4 = 24
