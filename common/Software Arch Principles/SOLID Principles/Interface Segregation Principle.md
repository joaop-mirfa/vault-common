#SOLID 

## Definition

[[Interfaces]] are used to define signatures of methods without specifying the exact logic inside them, like a contract

Interface Segregation Principle states thar if any particular interface member is not intended to be implemented by any of classes that implements this interface, it must not be in the interface. 

The client (the calling class or module) should not be forced to depend on an interface that it does not need.

	Many client-specific interfaces are better than one general-purpose interface.

- You should create interfaces.
- You should value small interfaces more.
- You should not try to create a multipurpose interface as “an interface to rule them all”.
-  you should separate the interface into logical pieces, based on the needs of the consumers.

can be considered a sub-set, or more specific form of the [[Single Reponsibility Principle]]


## why

The use of this principle helps to prevent confusion and also helps to cut down on semantic coupling-the idea that a developer has to know the specific implementation of the class to use it correctly.

very _fat_ interface that may confuse any of the calling clients

If there are multiple concerns represented by an interface, or the methods and properties are unclear, then it becomes difficult to know which methods should be called when.
### obs

- In c# we can inheritance for interfaces just like we can use for class
- If the method not implement all of contract of this interface, we are violate this principle
