# Stack Class

- It is a subclass of Vector.
- It implements LIFO (Last In First Out) structure.
- It has methods like `push()`, `pop()`, etc.

## Example

```java
import java.util.*;

public class TestJavaCollection4 {  
    public static void main(String args[]) {  
        Stack<String> stack = new Stack<String>();  
        stack.push("Ayush");  
        stack.push("Garvit");  
        stack.push("Amit");  
        stack.push("Ashish");  
        stack.push("Garima");  
        stack.pop();  
        
        Iterator<String> itr = stack.iterator();  
        while(itr.hasNext()) {  
            System.out.println(itr.next());  
        }  
    }  
}  


#Output

Ayush
Garvit
Amit
Ashish
