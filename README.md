# hollow-triangle-in-java
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int p=n;
        for(int i=0;i<n-1;i++){
                for(int l=0;l<p-1;l++){
                    System.out.print(" ");
                }
                p--;
                for(int j=0;j<=i;j++){
                    if(j==0||j==i){
                System.out.print("* ");}
                else{
                    System.out.print("  ");
                }
            }
            System.out.println();   
        }
        for(int i=0;i<n;i++){
            System.out.print("* ");
            
        }
    }
}


