
## HashSet Class

- It is a class which implements the Set interface.
- It stores the elements randomly.
- It cannot store duplicate elements.

## Example

```java
import java.util.*;

public class TestJavaCollection7 {  
    public static void main(String args[]) {  
        // Creating HashSet and adding elements  
        HashSet<String> set = new HashSet<String>();  
        set.add("Ravi");  
        set.add("Vijay");  
        set.add("Ravi");  
        set.add("Ajay");  
        
        // Traversing elements  
        Iterator<String> itr = set.iterator();  
        while(itr.hasNext()) {  
            System.out.println(itr.next());  
        }  
    }  
}  


# Output
Vijay
Ravi
Ajay
