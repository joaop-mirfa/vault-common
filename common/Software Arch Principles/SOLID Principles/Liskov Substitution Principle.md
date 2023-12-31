#SOLID 

The Liskov Substitution Principle says that an object inheriting from a base class, interface, or other abstraction must be semantically substitutable for the original abstraction. 

Even if the original abstraction is poorly named, the intent of that abstraction should not be changed by the specific implementations


	Let ∅(x) be a property provable about objects x of type T. Then, ∅(y) should be true for objects y of type S, where S is a subtype of T.



you should be able to swap an object of type T with an object of type S, where S is the 
subtype of T, without breaking your program’s correctness

polymorphic behavior is part and parcel of C# language features, but it is a developer’s 
responsibility to ensure that such a polymorphic setup doesn’t introduce any errors or inaccuracies into the  system

you can’t violate the [[Covariance & Contravariance]] in C#:
	The contravariance of method arguments in the subtype
	The covariance of return types in the subtype

## why

LSP focuses on preserving subtype behaviors, which leads to system stability. 

A type must be substitutable by its subtypes without altering the correctness of the application

