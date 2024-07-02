# print-all-even-numnbers-till-n
import java.util.Scanner;

public class loops {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("enter the value needed : ");
        int n = s.nextInt();
        for(int x = 0 ;x <= n ;x = x + 2 ){
         System.out.println(x);
        }
    }
}
