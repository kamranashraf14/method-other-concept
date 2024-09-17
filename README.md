# method-other-concept
pass by value not by reference babaaaa
import java.util.*;

public class Main {
    public static void main(String[] args) {
      
     String chacha = "became old";
     cond(chacha);
     
  }
  //  here uncle contains the value " become old" 
  //this uncle does,t care about the chacha
  // in java only there is pass by value not pass by reference
  
  static void  cond(String uncle){
    System.out.println(uncle);
  }
}
