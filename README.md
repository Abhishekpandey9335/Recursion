# Recursion
//print 1 to 50 numbers with the help of recursion

public class Main {
    public static void printNumb(int n){
        if(n==50){
            return;
        }
        System.out.println(n);
        printNumb(n+1);
    }
    public static void main(String[] args) {
        int n=1;
        printNumb(n);
    }

    }
