<!--  
 Practice Questions (Day 1)
 1 User se 2 numbers input lo aur unka sum, difference, product aur quotient print karo.
 2 Loop likho jo 1 se 10 tak numbers print kare.
 Solutions
 Q1:
 Q2: -->
 import java.util.Scanner;
 public class Q1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println("Sum = " + (a + b));
        System.out.println("Difference = " + (a - b));
        System.out.println("Product = " + (a * b));
        if(b != 0){
            System.out.println("Quotient = " + (a / b));
        } else {
            System.out.println("Cannot divide by zero!");
        }
    }
 }

 
 public class Q2 {
    public static void main(String[] args) {
        for(int i = 1; i <= 10; i++){
            System.out.println(i);
        }
    }
 }