# Iterator

- **Iterator**:
  - It is an interface.
  - It provides a facility to iterate through the elements in a forward direction only.
  - It is the root interface for all collection classes.

### Iterator Methods

1. `public boolean hasNext()`
   - It returns true if the iterator has more elements; otherwise, it returns false.

2. `public Object next()`
   - It returns the element and moves the cursor pointer to the next element.

3. `public void remove()`
   - It removes the last element returned by the iterator. It is less used.
