# Objects / Data Structures

- Object : Contains private variables and methods to manipulate and/or expose the private data
- Data Structure : Contains public variables and no methods
- Procedural code (code using data structures) makes it easy to add new functions without
  changing the existing data structures. OO code, on the other hand, makes it easy to add
  new classes without changing existing functions.
- Law of Demeter : a module should not know about the innards of the objects it manipulates

## Conclusion

- Objects expose behavior and hide data. This makes it easy to add new kinds of objects
  without changing existing behaviors. It also makes it hard to add new behaviors to existing
  objects.
- Data structures expose data and have no significant behavior. This makes it easy to
  add new behaviors to existing data structures but makes it hard to add new data structures
  to existing functions.
