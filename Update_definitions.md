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

**Exceptions**:
Errors detected during execution are called exceptions. An exception forces your program to output an error when something in the code is wrong. An exception causes the process to stop and move to thhe calling process unit it is handled. If it is not handled, the program will crash. 

**Unit Test**:
Unit Test is the first level of software testing where the testable portions of a software are tested. Unit Test are used to validate that each unit of the software performs as designed. 

**Constructors:**
Constructors are usedfor instantiating an object. The task of constructorsis to initializ(assign values) to the data members of the class when an object of class is created. The __init__() method is called the constructor and is always called when an object is created. 
Two types of Constructor:
1. Default Constructor: The default constructor is simple constructor which doesn’t accept any arguments.It’s definition has only one argument which is a reference to the instance being constructed.
2. Parameterized Constructor: constructor with parameters is known as parameterized constructor.The parameterized constructor take its first argument as a reference to the instance being constructed known as self and the rest of the arguments are provided by the programmer.

syntax of constructor declaration:
def __init__(self):
    # body of the constructor
    
**Factory**:
Factory method is a creational design pattern that solves the problem of creating produc objects without specifying their concreate classes. Factory method defines a method, that is used for creating objects. 

**Decorators:**
Decorators provide a simple syntax for calling higher-order functions. It is a function that takes another function and extends the behavior of the latter function without drastically changing or modifying it.

**Extend Class:**
Extend Class is basically to add new methods, not changing existing ones. Extending classes is to use a preprocessor that adds the ability to extend above the a usual code in python.

Here's an extending code example:

extend:testDottedQuad
def testDottedQuad(strObject):
    if not isinstance(strObject, basestring): return False
    listStrings = strObject.split('.')
    if len(listStrings) != 4: return False
    for strNum in listStrings:
        try:    val = int(strNum)
        except: return False
        if val < 0: return False
        if val > 255: return False
    return True
    
**CSV**:
Common-separate values (csv) is a type of plain text file that uses specific structuring to arrange tabular data. 

CSV example:
column 1 name,column 2 name, column 3 name
first row data 1,first row data 2,first row data 3
second row data 1,second row data 2,second row data 3

Each data point is separated by a comma. Usually, the first line identifies each piece of data (the name of a data column). Every subsequent line after that is actual data.

**Reading Files**:
There are a few ways to read text file. IF you need to extract a string that contains all characters in the file use: **file.read()**

code example: *file = open("testfile.text", "r")
              print file.read()*
              
The output of the command will display all text inside the file.

Another way to read a file is called a certain number of characters. this will read the first five characters of sotred data and return it as a string:

file = open(“testfile.txt”, “r”)
 
print file.read(5) 

Another way to read a file line by line is to use the readlin() function. If you want to see the first line of the file or the fourth. You would execute the readline() function as many times as possible to get the data you were looking for. 

Each time you run the method, it will return a string of characters that contains a single line of information from the file:

file = open(“testfile.txt”, “r”) 
print file.readline(): 
    
