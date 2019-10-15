
For object oriented programming there are 23 design patterns mentioned by GOF

Mainly these patterns revolve arround ideas of  - classes vs objects, abstarct class vs interfaces, inheritance vs composition, cloning objects,
runtime dynamic behavior vs static behavior, caching objects, pub-sub, and separating data from functionality.

Sometime they looks the same but their intent might be different.

## Design Patterns 

### General Principals 
- For more flexibility,  consider composition over inheritance or compose object at runtime than defining at class or template level.
- Inheritance need more knowledge of code and difficult to trace
- Create larger object with small objects which can be dynamically changed at runtime.

### Design Patterns  are classified as follow 

### Creational Patterns - Used to create object 

  1. Abstract Factory [create family of related objects]
  2.  Builder [build objects by part]
  3.  Factory Method [create object on runtime with predefined interface]
  4. Prototype or Cloning  [copy object in memory]
  5. Singleton [One object per process]
  
 ### Structural Patterns - Relationship between classes or Objects 
 6. Adapter [work with already existing past incompactible interfaces]
 7. Bridge [work with abstraction and implementation so that both can chnage independently in future.]
 8. Composite [Tree Structure]
 9. Decorator [Additional functionality at runtime]
 10. Facade [Simplified interface to complex sub-system]
 11. Flyweight [Named after boxing which has lightest boxers, indicating reduced memory footprint]
 12. Proxy [surrogate or placeholder for objects whose creation is costly]

### Behavioural Patterns - Communication between classes or Objects 
13. Chain of responsibility [ dynamic execution sequence]
14. Command [chain of instructions which can be un-done]
15. Interpreter [understand language based expressions and map and execute activity]
16. Iterator [walk over aggregate of objects without concerning underlaying implementation]
17. Mediator [Intervene communication between two or more objects]
18. Memento [store complex state of object and restore later if needed]
19. Observer [publish-subscrive event model/listener/event handler and publishers]
20. State [Based on state of object it may behave differently example - HHTP response read  with closed state]
21. Strategy [Family of interchangeable algorithms which can be chosen at runtime based on inputs]
22. Template Method [template method with list of basic steps, steps implementation can be changed]
23. Visitor [Separate complex data classes from functionality. Ex. Visitor can process data for each node in tree, instead of each node having same functionality]
 

#### Confusing design patterns 
- Abstract Factory vs Factory Method
- Adapter vs Bridge
- Adapter vs Bridge vs decorator vs facade vs proxy 
- Memento vs State 
- Stategy vs Template 
- Composite vs visitor 
- Command vs interpreter 


Also you should know [SOLID](https://en.wikipedia.org/wiki/SOLID) principal 

- ##### Single responsibility principle

  A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
  
- ##### Open–closed principle

  "Software entities ... should be open for extension, but closed for modification."

- #####  Liskov substitution principle

  "Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.

- #####  Interface segregation principle

  "Many client-specific interfaces are better than one general-purpose interface."

- #####  Dependency inversion principle

  One should "depend upon abstractions, [not] concretions."

