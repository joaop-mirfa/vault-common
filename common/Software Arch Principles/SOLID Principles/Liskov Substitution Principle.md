#SOLID 


	Let ∅(x) be a property provable about objects x of type T. Then, ∅(y) should be true for objects y of type S, where S is a subtype of T.

LSP focuses on preserving subtype behaviors, which leads to system stability. 

you should be able to swap an object of type T with an object of type S, where S is the 
subtype of T, without breaking your program’s correctness

A type must be substitutable by its subtypes without altering the correctness of the application


polymorphic behavior is part and parcel of C# language features, but it is a developer’s 
responsibility to ensure that such a polymorphic setup doesn’t introduce any errors or inaccuracies into the  system

you can’t violate the [[Covariance & Contravariance]] in C#:
	The contravariance of method arguments in the subtype
	The covariance of return types in the subtype

