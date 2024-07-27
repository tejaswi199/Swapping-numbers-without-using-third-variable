# Swapping-numbers-without-using-third-variable
import java.util.*;
public class Main{
    public static void main(String[] args){
        int a=5;
        int b=4;
        System.out.println("Befor swapping:" + a +" "+b);
        a=a^b;
        b=a^b;
        a=a^b;
        System.out.println("After swapping:" +a +" "+b);
        
      
    }
}
