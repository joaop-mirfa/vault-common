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


	When the business perception and context has changed, then you have a reason to change the class.

The reason that a class should have one reason to change, instead of one reason to exist, is the business context in which you are building the system.

The key point of deciding when a class should change is not based on a purely logical separation of concepts, but rather the business’s perception of the concept. When the business perception and context has changed, then you have a reason to change the class

To simplify, its about not mix responsabilities,

	Gather together things that change for same reason. Separate things that change for diferent reasons.


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

## How to reduce/minimize erros of this principles

- Ter nitidez sobre o problema aquela funcionalidade/pedaço de código deve realizar
- Manter nivel de Cohesion. Todas as unidades precisam estar relacionadas/coesas para resolver o que se propõe
- Evitar "acomplamento mental". Não fazer um design pensando no futuro serviço do frontend ou serviço que irá consumir tal funcionalidade, mas sim pensar em atender o problema que vc precisa resolver
	- O contexto deve ajudar a ter clareza mas não deve ser fator fundamental para um decisão de funcionario

## How to metrify the SRP

- Acomplamento
	- Acoplamento só cresce dentro da sua classe
- Fan-Out
	- Numero de chamadas que uma classe faz para outras classes, 
		- se esta recebendo fazendo muitas chamadas a outraas classes, pode estar tendo uma responsabilidade maior que deveria
- RFC (Response for a class)
	- Numero de interface publica disponíveis para outra classe utilizar (essa quantidade faz sentido)
- LCOM (Lack of cohesion of methods)
	- Metodos de uma classe estão conectados com os atributos da classe

### Obs

1. There is no need to have multiple classes that all hold just one function. Try to find the right balance when defining responsibilities and classes.
2. to split the big code in some single responsability functions, we need to analize the [[Class Cohesion]] of this part of code
3. we need to every time think about the SRP when creating some think, to not mix responsabilities, but probally that occurs
5. 

## Sample

- Software layers
	- External Services
	- Frameworks
	- Protocols
	- UI


### Cards



## reference

https://www.youtube.com/watch?v=gNZpaw6-3xY&list=PLVHlvMRWE0Y4APZiLYyUyWOyMKm1H9zwm&index=2&t=275s
https://stackify.com/solid-design-principles/
https://www.codemag.com/article/1001061