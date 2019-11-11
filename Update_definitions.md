# SOME USEFUL DEFINITIONS 

**How Python uses Indentation to control Flow:**  
Generally , programming languaged uses braces {} to define a block of code. Instead, Python uses indentation to define a block. A code block, 
(for example: a loop, a function etc.) starts with indentation and ends with the firt unintended line.Amount of indentation must be consistent 
for all that block.
 
**Don't Repeat Yourself:**  
Don’t Repeat Yourself is a principle of software development. The focus of Don't repeat yourself is to avoid repetition of codes. 
First important reaon is that when you write code that performs the same tasks over and over again, any modification of one task requires 
the same change to be made to every single instance of that task! Editing every instance of a task is a lot of work.
By implementing Don't Repeat Yoursel code strategies, you can make your code:  
 1.Easier to follow and read for yourself and for other developers  
 2.Easier to update because you only have to update your code once, rather than every that code block is used
You can use loops, conditional statements and functions to aviod code repetition. 

**Design Patterns from Gang of Four:**  
A design pattern is a reusable solution to a recurring problem in software design. It is not a finished piece of code but a template that 
helps to solve a particular problem or family of problems.The gang of four, authors Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides, initiated the concept of Design Pattern in Software 
development, so that their work is known as "Gang of Four Design Patterns".  
Gang of Four Design Patterns structured under three categories:  
* **Creational**: The design patterns that deal with the creation of an object.  
* **Structural**: The design patterns in this category deals with the class structure such as Inheritance and Composition.  
* **Behavioral**: This type of design patterns provide solution for the better interaction between objects, how to provide lose coupling, and 
flexibility to extend easily in future.

**Class**:  
When a user defines an object in python, class is a blueprint that defines the nature of a future object from classes. It contains   all the details about the object based on the descriptions we made. We define a class using the keyword 'class'.

**Object**:  
object is collection of variables and functions into a single entity. Objects get their variables and functions from the classes.  
Also, an object is called as an instance of a class and the process of creating this object is called instantiation.

**Static**:  
Static methods, similar to class methods, are methods that are bound to a class rather than its object.They do not require a class   instance creation. So, are not dependent on the state of the object. 
The difference between a static method and a class method is:  
* Static method does not have any information about the class and only deals with the parameters.  
* In a static method, we don’t need the self to be passed as the first argument.  
* Class method functions with the class since its parameter is always the class.  


Property / Attribute:  
**Attribute** is charactheristic of an object  
**Property** is an attribute of a class which results from binding a setter,getter or delete methods. to an attribute. This makes   attribute a descriptor and so that specified forms of access are available for thoe methods.  
  
**Method**: 
Methods are basicly functions defined inside the body of the class and they are used to perform operations that sometimes utilize the actual attributes of the object we created. So, methods are functions acting on an object itself into account through the use of the self keyword.
