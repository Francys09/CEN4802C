# CEN4802C
public class Fibonacci {
    public static void main(String[] args) {
        int n = 10;
        int y = fibonacci(n);
        System.out.println("The " + n + "th term of the Fibonacci sequence is " + y + ".");
    }

    public static int fibonacci(int n) {
        if(n == 0) {
            return 0;
        }
        if(n == 1) {
            return 1;
        }
        
        return fibonacci(n - 1) + fibonacci(n - 2);
    }
}
