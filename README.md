
import java.util.*;
public class L3{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        System.out.println("enter the number");
        int n=sc.nextInt();
        
        for(int i=1;i<=n;i++){
            for(int j=2;j<=i;j++){
                System.out.print("*");
            }
            System.out.println("*");
        }
    }




}
