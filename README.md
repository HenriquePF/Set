## Set<T>

## Main Topics:
- Represents a set of elements;
- It doesn't accept repetitions;
- Elements of the set don't have position;
- Access, insert and remove of elements are quick;
- Offers eficient group operations: retainAll, addAll, removeAll;

## Few important methods:
- add(obj), remove(obj), contains(obj);
  - Based on equals and HashCode;
  - If equals and hashcode doesn't exist, it's used comparison of pointers;

- clear();
- size();
- removeIf(predicate);

- addAll(other) - union: add in the set the elements of another set, without repetition;
- retainAll(other) - intersection: remove from the set the elements not contained in other;
- removeAll(other) - difference: remove from the set the elements contained in other;

  **-----------------------------------------------------------------------------------**
  
  
  **Remember that i'm in learning process, i'm open for constructive criticism and tips, please, feel free to help, Thanks!**
