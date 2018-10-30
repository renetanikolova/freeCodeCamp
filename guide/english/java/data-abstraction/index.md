---
title: Data Abstraction
---

## Definition
As per dictionary, abstraction is the quality of dealing with ideas rather than events.

Likewise in Object-oriented programming, abstraction is a process of hiding the implementation details from the user, only the functionality will be provided to the user. In other words, the user will have the information on what the object does instead of how it does it.

In Java, abstraction is achieved using Abstract classes and interfaces.

Interface is a piece of code defining a set of operations that other code (classes) must implement.
Interfaces were introduced in Java to enhance Java’s single-inheritance model, multiple inheritance created too many problems for programmers and compiler writers. 
All methods in interface are public, we may not write it every time, like all of them are abstract, but we never write the key word abstract.
The interface should have at least one method but not too many.

Abstract classes are classes, which should contain at least one abstract method. Note that we can not create instances from abstract class.
We 'extends' an abstract class and we are obligated to implement all of the abstract methods it contains.

Abstract class vs. Interface:
All of the methods in one Interface are abstract, while in abstract class we can have methods with body.
We can implement many interfaces, but we can inherit only one abstract class.

Advantages using interfaces:
It decouples your code.
Helps in team corporation.
Increase your flexibility.


## Resources
[Tutorials Point - Java Abstract classes and interfaces](https://www.tutorialspoint.com/java/java_abstraction.htm)
<br />
[Java Tutorials - Java Abstract methods and classes](https://docs.oracle.com/javase/tutorial/java/IandI/abstract.html)

