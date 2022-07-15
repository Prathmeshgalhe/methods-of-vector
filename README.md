# methods-of-vector
import java.util.*;  
public class VectorExample1 {  
       public static void main(String args[]) {  
        
          Vector<String> vec = new Vector<String>(4);  
         
          vec.add("Tiger");  
          vec.add("Lion");  
          vec.add("Dog");  
          vec.add("Elephant");  
          
          System.out.println("Size is: "+vec.size());  
          System.out.println("Default capacity is: "+vec.capacity());  
          
          System.out.println("Vector element is: "+vec);  
          vec.addElement("Rat");  
          vec.addElement("Cat");  
          vec.addElement("Deer");  
          
          System.out.println("Size after addition: "+vec.size());  
          System.out.println("Capacity after addition is: "+vec.capacity());  
          
          System.out.println("Elements are: "+vec);  
               
            
       }  
}  
