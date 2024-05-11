# LinkedHashSet Class

- `LinkedHashSet` class extends `HashSet` and implements the `Set` interface.
- It contains unique elements, meaning it doesn't add duplicate elements.
- It maintains the insertion positions, storing the elements as they are inserted.

## Example

```java
import java.util.*;

public class TestJavaCollection8 {  
    public static void main(String args[]) {  
        LinkedHashSet<String> set = new LinkedHashSet<String>();  
        set.add("Ravi");  
        set.add("Vijay");  
        set.add("Ravi");  
        set.add("Ajay");  
        
        Iterator<String> itr = set.iterator();  
        while(itr.hasNext()) {  
            System.out.println(itr.next());  
        }  
    }  
}  

# Output
Ravi
Vijay
Ajay
