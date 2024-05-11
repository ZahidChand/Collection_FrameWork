# Vector Class

- Vector is a class which implements the List interface.
- It is a synchronized class.
- It is thread-safe.
- Its execution is slow.
- Elements can be saved using `add()` or `addElement()`, where `add()` is not synchronized and `addElement()` is synchronized.

## Example

```java
import java.util.*;

public class TestJavaCollection3 {  
    public static void main(String args[]) {  
        Vector<String> v = new Vector<String>();  
        v.add("Ayush");  
        v.add("Amit");  
        v.add("Ashish");  
        v.add("Garima");  
        
        Iterator<String> itr = v.iterator();  
        while(itr.hasNext()) {  
            System.out.println(itr.next());  
        }  
    }  
}  

# Output

Ayush
Amit
Ashish
Garima
