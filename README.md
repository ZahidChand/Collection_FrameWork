# Collection Framework

Collection framework provides an architecture that is used to store and manipulate groups of objects. It also provides different interfaces like Set, List, Queue, and other classes like ArrayList, Vector, LinkedList, PriorityQueue, HashSet, LinkedHashSet, TreeSet.

## Hierarchy of Collection Framework

```
               Iterable
                   |
                 Collection
            /      |      \
          Set     List    Queue
            |       |        |
       SortedSet    |     Deque
                    |
               SortedList
```

- **Iterator**:
  - It is an interface.
  - It provides facility to iterate through the elements in a forward direction only.
  - It is a root interface for all collection classes.

### List Interface

- List is an interface.
- Values are stored in the list interface as they are.
- It can have duplicate values.
- Classes like LinkedList, ArrayList, Vector, and Stack implement the List interface.
- There are various methods in List interface that can be used to insert, delete, and access the elements from the list.

### ArrayList Class

- It is a class which implements List interface.
- It maintains the insertion order.
- It can store duplicate elements.

### Vector Class

- Vector is a class which implements List interface.
- It is a synchronized class.
- It is thread safe.
- Its execution is slow.
- Elements can be saved using add() or addElement(). Here add() is not synchronized and addElement() is synchronized.

### Stack Class

- It is a subclass of Vector.
- It implements LIFO (Last In First Out) structure.
- It has methods like push(), pop(), etc.

### Set Interface

- It is an interface.
- It does not store duplicate elements.
- At most only one element can be null.
- Classes like HashSet, LinkedHashSet, and TreeSet implement Set interface.

#### HashSet Class

- It is a class which implements Set interface.
- It stores the elements randomly.
- It cannot store duplicate elements.

#### LinkedHashSet Class

- LinkedHashSet class extends HashSet and implements Set interface.
- It contains unique elements which means it doesn't add duplicate elements.
- It maintains the insertion positions means it stores the elements as they are inserted.

### SortedSet Interface

- SortedSet is an interface.
- It doesn't store duplicate elements.
- It stores elements in ascending order.

### TreeSet Class

- TreeSet implements Set interface that uses a tree for storage.
- Like HashSet, TreeSet also contains unique elements.
- TreeSet has fast access and retrieval time.
- TreeSet stores elements in ascending order.
