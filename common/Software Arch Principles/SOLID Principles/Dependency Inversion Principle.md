#SOLID 

## Definition

Dependency Inversion Principle states that a higher level object should never depend on a concrete implementation of a lower-level object. Both should depend on abstractions.


	One should “depend upon abstractions, [not] concretions.

using interfaces is the best way to approach the DIP. 
	interfaces are more flexible, more powerful, and better suited to design contracts.

you want to work with a standard interface. Furthermore, you want to ensure that you can replace the implementation without violating the expectations of that interface

The higher-level policy should define an abstraction that it will call out to, where some detail implementation executes the requested action

## obs

- abstract classes are also abstractions, but you should depend on interfaces whenever 
possible instead.
	1. An abstract class is an abstraction but is not 100% abstract
	2. Abstract classes are used to encapsulate default behaviors that you can then inherit in sub-classes N
