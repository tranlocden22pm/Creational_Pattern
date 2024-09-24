#What are Design Patterns?

Design patterns are solutions to software design problems you find again and again in real-world application development. Patterns are about reusable designs and interactions of objects.
The 23 Gang of Four (GoF) patterns are generally considered the foundation for all other patterns. They are categorized in three groups: Creational, Structural, and Behavioral (for a complete list see below). This reference provides source code for each of the 23 GoF patterns.
---------------------------------------------------------------------------------
C# Design Patterns
To give you a head start, the C# source code for each pattern is provided in 3 forms: structural, real-world, and .NET optimized.
Structural code uses type names as defined in the pattern definition and UML diagrams. Real-world code provides real-world programming situations where you may use these patterns. The third form, .NET optimized, demonstrates design patterns that fully exploit the latest C# and .NET features, such as, generics, reflection, lambdas, primary constructors, and more.
---------------------------------------------------------------------------------
#Creational Patterns

Abstract Factory -	Creates an instance of several families of classes
Builder -	Separates object construction from its representation
Factory - Method	Creates an instance of several derived classes
Prototype -	A fully initialized instance to be copied or cloned
Singleton -	A class of which only a single instance can exist
---------------------------------------------------------------------------------

#Structural Patterns

Adapter -	Match interfaces of different classes
Bridge -	Separates an object’s interface from its implementation
Composite -	A tree structure of simple and composite objects
Decorator -	Add responsibilities to objects dynamically
Facade -	A single class that represents an entire subsystem
Flyweight -	A fine-grained instance used for efficient sharing
Proxy -	An object representing another object
---------------------------------------------------------------------------------

#Behavioral Patterns

Chain of Resp -	A way of passing a request between a chain of objects
Command -	Encapsulate a command request as an object
Interpreter -	A way to include language elements in a program
Iterator -	Sequentially access the elements of a collection
Mediator -	Defines simplified communication between classes
Memento -	Capture and restore an object's internal state
Observer -	A way of notifying change to a number of classes
State -	Alter an object's behavior when its state changes
Strategy -	Encapsulates an algorithm inside a class
Template - Method	Defer the exact steps of an algorithm to a subclass
Visitor -	Defines a new operation to a class without change
