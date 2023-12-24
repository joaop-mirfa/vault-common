#SOLID 

## Definition

Single responibility principle states that, for every self-containes unit of code (like class) there should be one and only one reason to change (had only a single responsibility/purpose)

Class should be responsible for only one specific functionality

Each of these components is atomic (unsplittable), self-contained and can be easily replaced


	There should never be more than one reason for a class to change.
		 Robert C. Martin

So, this may seem counter-intuitive at first. Wouldn’t it be easier to say that a class should only have one reason to exist?
	 If you take it to that extreme and build classes that have one reason to exist, you may end up with only one method per class
		 -> This would cause a large sprawl of classe causing the system to be difficult to understand and difficult to change


So


## Why

- it makes your software easier to implement 
	-  make our classes more reusable and create more flexible systems
	-  classes more readable.
		- Fewer responsibilities lead to less code, and less code is simpler to visualize
	
- Code that not implement this principles can create [[God Object]]
	- Will be relatively difficult to modify, because everything is in one place
	
- Applications are born to change.
	- prevents unexpected side effects of future changes.
	- help maintain applications. Since you know the only thing a class does before updating it, you  can quickly foresee the impact on the system 
	
-  reduce [[coupling]]
	- avoids any unnecessary, technical coupling between responsibilities and reduces the probability that you need to change your class

- reduce merge conflicts
	- if 2 developers works in same file, if they alter diferent functions, reduce the probability of error

### Obs

1. There is no need to have multiple classes that all hold just one function. Try to find the right balance when defining responsibilities and classes.
2. to split the big code in some single responsability functions, we need to analize the [[Class Cohesion]] of this part of code

## Sample
*** para desenvolver



### Cards



## reference

https://www.youtube.com/watch?v=gNZpaw6-3xY&list=PLVHlvMRWE0Y4APZiLYyUyWOyMKm1H9zwm&index=2&t=275s
https://stackify.com/solid-design-principles/

