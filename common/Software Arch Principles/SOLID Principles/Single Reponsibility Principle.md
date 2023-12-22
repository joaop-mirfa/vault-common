#SOLID 

## Definition

Single responibility principle states that, for every self-containes unit of code (like class) there should be one and only one reason to change (had only a single responsibility/purpose)

Class should be responsible for only one specific functionality

Each of these components is atomic (unsplittable), self-contained and can be easily replaced


	There should never be more than one reason for a class to change.
		 Robert C. Martin

## Why

- it makes your software easier to implement 
	-  make our classes more reusable and create more flexible systems
	-  classes more readable. Fewer responsibilities lead to less code, and less code 
is simpler to visualize
	
- Code that not implement this principles can create [[God Object]]
	- Will be relatively difficult to modify, because everything is in one place
	
- Applications are born to change.
	- prevents unexpected side effects of future changes.
	- help maintain applications. Since you know the only thing a class does before updating it, you  can quickly foresee the impact on the system 
	
- avoids any unnecessary, technical coupling between responsibilities and reduces the probability that you need to change your class

it makes your software easier to implement and prevents unexpected side effects of future changes.

To follow this principle, your class isn’t allowed to have more than one responsibility, e.g., the management of entities or the conversion of data types. 
This avoids any unnecessary, technical coupling between responsibilities and reduces the probability that you need to change your class. It also lowers the complexity of each change because it reduces the number of dependent classes that are affected by it. However, be reasonable.
There is no need to have multiple classes that all hold just one function. Try to find the right balance when defining responsibilities and classes