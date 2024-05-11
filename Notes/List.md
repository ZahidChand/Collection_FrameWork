# List Interface

- **List** is an interface.
- Values are stored in the List interface as they are.
- It can have duplicate values.
- The following classes implement the List interface:
  - LinkedList
  - ArrayList
  - Vector
  - Stack
- There are various methods in the List interface that can be used to insert, delete, and access the elements from the list.

Example:# List Interface Initialization

```java
List <data-type> list1 = new ArrayList();  
List <data-type> list2 = new LinkedList();  
List <data-type> list3 = new Vector();  
List <data-type> list4 = new Stack();  

# Example Code

```java
import java.util.*;

public class TestJavaCollection2 {  
    public static void main(String args[]) {  
        LinkedList<String> al = new LinkedList<String>();  
        al.add("Ravi");  
        al.add("Vijay");  
        al.add("Ravi");  
        al.add("Ajay");  
        Iterator<String> itr = al.iterator();  
        while(itr.hasNext()) {  
            System.out.println(itr.next());  
        }  
    }  
}  

# Output

Ravi
Vijay
Ravi
Ajay
