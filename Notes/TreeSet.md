# TreeSet Class

- `TreeSet` implements the `Set` interface and uses a tree for storage.
- Like `HashSet`, `TreeSet` also contains unique elements.
- `TreeSet` has fast access and retrieval time.
- `TreeSet` stores elements in ascending order.

## Example

```java
import java.util.*;

public class TestJavaCollection9 {  
    public static void main(String args[]) {  
        // Creating and adding elements  
        TreeSet<String> set = new TreeSet<String>();  
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
Ajay
Ravi
Vijay
