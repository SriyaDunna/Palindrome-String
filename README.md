# Palindrome-String
import java.util.*;   
class Palindrome
{  
   public static void main(String args[])  
   {  
      String actual,reverse = ""; 
      Scanner in = new Scanner(System.in);   
      System.out.println("Enter a string:");  
      actual = in.nextLine();   
      int length = actual.length();   
      for ( int i = length - 1; i >= 0; i-- )  
         reverse = reverse + actual.charAt(i);  
      if (actual.equals(reverse))  
         System.out.println("Entered string is a palindrome.");  
      else  
         System.out.println("Entered string is not a palindrome.");   
   }  
}
