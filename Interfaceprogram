# Interfaceprogram
coding:
package interfaceprogram;
import java.util.Scanner;
interface Calculator{
    double add(double a, double b);
    double subtract(double a, double b);
    double multiply(double a, double b);
    double divide(double a, double b);
}
class SimpleCalculator implements Calculator{
    @Override
    public double add(double a,double b){
        return a+b;
    }
    public double subtract(double a,double b){
        return a-b;
    }
    public double multiply(double a,double b){
        return a*b;
    }
    public double divide(double a,double b){
        if(b==0){
            System.out.println("Error:Division by zero is not allowed! ");
            return Double.NaN;
        }
        return a/b;
    }
}
    public class CalculateProgram{
            public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
        Calculator calculator = new SimpleCalculator();
        System.out.println("Welcome to the Simple Calculator!");
        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();
        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();
        System.out.println("\nResults:");
        System.out.println("Addition: " + calculator.add(num1, num2));
        System.out.println("Subtraction: " + calculator.subtract(num1, num2));
        System.out.println("Multiplication: " + calculator.multiply(num1, num2));
        System.out.println("Division: " + calculator.divide(num1, num2));
        scanner.close();
    }
    }

Output:

Welcome to the Simple Calculator!
Enter the first number: 3
Enter the second number: 6

Results:
Addition: 9.0
Subtraction: -3.0
Multiplication: 18.0
Division: 0.5

