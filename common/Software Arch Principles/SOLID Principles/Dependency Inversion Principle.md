#SOLID 

## Definition

Dependency Inversion Principle states that a higher level object should never depend on a concrete implementation of a lower-level object. Both should depend on abstractions.


	One should “depend upon abstractions, [not] concretions.

using interfaces is the best way to approach the 
DIP. Of course, abstract classes are also abstractions, but you should depend on interfaces whenever 
possible instead.
Why not use abstract classes, you might think? An abstract class is an abstraction but is not 100% 
abstract, and if it is, you should replace it with an interface. Abstract classes are used to encapsulate 
default behaviors that you can then inherit in sub-classes. They are helpful, but interfaces are more 
flexible, more powerful, and better suited to design contracts. N
