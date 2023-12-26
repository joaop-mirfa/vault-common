#SOLID 

## Definition

[[Interfaces]] are used to define signatures of methods without specifying the exact logic inside them, like a contract

Interface Segregation Principle states thar if any particular interface member is not intended to be implemented by any of classes that implements this interface, it must not be in the interface


	Many client-specific interfaces are better than one general-purpose interface.

- You should create interfaces.
- You should value small interfaces more.
- You should not try to create a multipurpose interface as “an interface to rule them all”.
-  you should separate the interface into logical pieces, based on the needs of the consumers.
- 
### obs

- In c# we can inheritance for interfaces just like we can use for class
- If the method not implement all of contract of this interface, we are violate this principle
