#SOLID 

## Definition

Single responibility principle states that, for every self-containes unit of code (like class) there should be one and only one reason to change (had only a single responsibility)

Class should be responsible for only one specific functionality

Each of these components is atomic (unsplittable), self-contained and can be easily replaced


	There should never be more than one reason for a class to change.
		 Robert C. Martin

## Why



To follow this principle, your class isn’t allowed to have more than one responsibility, e.g., the management of entities or the conversion of data types. This avoids any unnecessary, technical coupling between responsibilities and reduces the probability that you need to change your class. It also lowers the complexity of each change because it reduces the number of dependent classes that are affected by it. However, be reasonable.
There is no need to have multiple classes that all hold just one function. Try to find the right balance when defining responsibilities and classes