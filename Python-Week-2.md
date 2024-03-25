
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

A class is like an object constructor or a blueprint for creating objects.

## Instance Attributes


