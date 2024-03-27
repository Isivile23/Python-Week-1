
# Python-Week-2
# Anatomy of a function

Python functions is a block of statements that returns a specific task.
Benefits of using Function:
* Increase Code Readability
* Increase Code Reusability
* Functions can take arguments, allowing you to pass data into function and customize its behaviour.
* Fuctions can return values, which can be used in other parts of your code. 

## The syntax to declare a function:

def function_name(parameters):
     # statement
     return expression

     
## Types of functions in Python:

* Built-in library function: These are standard functions in Python that are available to use.
* User-defined function: We ca create our own functions based on our requirements.

## Calling a function

Use function name followed by ()

## Parameters and arguments

They can be used for samething: information that is passed into a function.
Parameter is the variable listed inside the parantheses in the function definition.
An argument is the value thst is sent to the function when it is called.

## Function Arguments

* Required Arguments: These are parameters that must be provided when calling a fuction. If a required argument is missed, you will get an error.
* Default Arguments: You can assign default values to parameters during function definition. If a corresponding argument is not provided during a call, the default value gets used.
* Arbitrary Arguments (*args): This allows a function to accept any number of positional arguments beyond the defined parameters. These arguments are stored as a tuple within the function.
* Keyword Arguments (**kwargs): This allows you to pass arguments by keyword name instead of position. Keyword arguments are stored as a dictionary within the function.
* Positional arguments: These are arguments passed in the order they are defined in the functions parameter list.

## Function scope

Function scope refers to the visibility and accessibility of variables within functions.

Different Scopes in Python:

### Local scope(Innermost):

* Variables defined inside a function are local to that function and cannot be accessed directly ffrom outside the function.
* Local variables are created when the function is called and destroyed when the function finishes executing.
* This prevents accidental modification of variables from other parts of your code.

### Enclosing Scope (Outer Function - for Nested Function):

* In nested functions, the inner function has access to variable defined in its enclosing function.
* This allows you to share data between inner and outer functions without making the variable global.

### Global Scope (Outermost):

* Variables defined outside of all functions are in the global scope
* They are accessible from anywhere in your program, including all functions.
* Its generally recommended to minimize the use of global variables as they can make code harder to understand and maintain.

## Recursion 

Python accepts function recursion, which means a defined function can call itself.
Recursion is a common mathematical and programming concept. It means that a function calls itself. 
This has the benefit of meaning that you can loop through data to reach a result.

* tri_recursion() is a function that we have defined to call itself ("recurse").

## Lambda Function

Lambda function is a small anonymous function.
A Lambda function can take any number of arguments, but can only have one expression.

### Syntax
lambda arguments : expression

## Why use lambda functions
The power of lambda is better shown when you use them as an anonymous function inside another function.

# Anatomy of a class

A class is a collection of objects. It contains the blueprints or the prototype from which the objects are being created. It is a logical entity that contains some attributes and methods.

## Instance Attributes

* Variables that are unique to each object (instance) of a class.
* Used to store data that varies among objects of the same class.
* Define them within the __init__() method (constructor) of a class using the self keyword.

## Static Attributes

* Variables that belong to the class itself, shared by all instances of that class.
* Defined at the class level, outside of any methods.
* Accessed directly using the class name, not through object instances.

## Instance and static methods

Instance methods:
* They are defined like regular functions within a class.
* First argument (self) refers to the object instance itself
* Can access both instance variables (specific to the object) and class variables (shared by all instances)

## Static methods

* They are defined using the @staticmethod decorator.
* Do not take self as an argument.
* Can only access class variables, not instance variables.
* Useful for utility functions related to the class but not specific to objects.

## Inheritance

### Class inheritance

Inheritance in Python is a fundamental concept in object-oriented programming (OOP) that allows you to create new classes (subclasses, derived classes, child classes) based on existing classes (superclasses, base classes, parent classes).
It provides a powerful mechanism for code reusability, promoting code organization and maintainability. 
The Subclass inherits all the public methods and attributes from a Superclass. The subclass can then add its own specific methods and attributes , or override inherited methods to provide custom behavior.

### Concepts:

* Superclass (Base Class, Parent Class): The original class that provides properties and methods to inhering classes.
* Subclass (Derived Class, Child Class): A new class created from a superclass, inheriting its attributes nd fuctionalities.

### Benefits of Inheritance

* Code Reusability
* Maintainability
* Real-world Modeling

# Handling Errors and Exceptions

Exceptions are determined during runtime and can be retried.
Errors can not be retried.
Errors and exceptions are basically the same thing.
All python errors and exceptions stem from a class called base exception.
The base exception class provides useful and powerful properties to exceptions such as halting code execution and providing information about why and how the execution was halted.

![image](https://github.com/Isivile23/Python-Week-1/assets/162969923/ec9ca693-6896-4c08-ba9a-02b1e4eabfc1)


## Managing and Handling Exceptions

* The try block lets you test a block of code for errors.
* The except block lets you handle the error.
* The else block lets you execute code when there is no error.
* The finally block lets you execute code, regardless of the result of the try and except blocks.

# Threads and processes

* Threads: is a flow of execution. Like a seperate order of instructions.
* GIL = (Global interpreter lock) allows only one thread to hold the control of the Python interpreter at any one time.
* cpu bound = program/task spends most of its time waiting for internal events (CPU intensive) multiprocessing.
* io bound = program/task spends most of its time waiting for external events (user input, web scrabing) multithreading.

# Fundamentals of working with files


## The open()function:
This is your gateway intercating with file. It opens a file for various operations and returns a file object.

The syntax is:

![image](https://github.com/Isivile23/Python-Week-1/assets/162969923/f042372a-5ab0-41c4-8d1b-4061dbc6334c)

* filename: The name of the file you want to work with.
* mode: A string indicating the access mode for the file

## File Modes

The mode argument in open() specifies how you want to interact with the file. Here are some common modes:

* 'r': Open for reading (default). Raises an error if the file does not exist.
* 'w'": Open for writing. Creates new files if it does not exist, otherwise truncates (clears) the existing content.
* 'a': Open for appending. Creates a new file if it does not exist, otherwise adds new data to the end of the existing file.
* 'x': Open for exclusive creation. Creates a new file and raises an error if the file already exists.
* 'r+': Open for reading and writing. Allows both reading and modifying the content.
* 'a+': Open for appending and reading. Similar to 'a' but allows reading as well.

## Reading from Files:

Once you have a file object opened in read mode ('r'), you can use methods to access its content:

* read(size): Reads a specific number of bytes from file and returns it as a string (or bytes objects in binary mode). If size is omitted, reads the entire file.
* readline(): Reads a single line from the file (including the newline character) and returns it as a string.
* readlines(): Reads all line from the file and returns them as a list of strings, where each element is a line.

## Writing to File:

Whem a file is opened in write mode ('w') or append mode ('a'), you can use the write() method to write data to the file:

* write(string): Writes the string to the file. Data is encoded accordon to the files encoding (usually UTF-8).







