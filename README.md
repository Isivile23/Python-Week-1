# Python-Week-1
# Python Introduction: Basics of Python

Python is a programming language used by many large organization such as Google, Yahoo and IBM.
Jupyter Notebook is a web application where you write and execute python programs. 
"#" is a comment symbol.

# Variables and types

Variables contain lowercases, uppercases and underscore. In Python variable names begin with a lowercase.
We have different types of variable: String, float, Boolean, Complex and integer.
Data structure stores a list of values in a variable.
Sets are declared in curly braces.
Tuples are similar to list but they cannot be modified once declared.They are useful when you need to store large amount of data in memory.
Dictionary is a collection of key value pairs.
Dictionaries are declared using curly braces and accessed using keys.

# Operators 

Operators are instructions that perform operations on variables and values in python.
The most familiar type of operator is the arithmetic operator.It is used for mathematical calculations.
Examples of arithmetic operators are:
Addition operator
Multiplication operator
Exponent operator
Division 
Modulus Operator

Another set of operators in Python are comparison operators, logical operators, identity operators and membership operators.

Comparison Operators evaluate two variables or values and produces a Boolean result, either true or false.
Logical Operators, such as "and", "or" and "not" operate on Boolean values.
Membership operators "in" and "not" are used to check whether a value is present in a sequence or not.

# Control Flow

if statement is one of the control flow in progarmming. It allows you to execute a code only if the statement or condition is true.
You can add more code under the if statement by indenting it further.
If you add an else statement the code under that will be executed if the condition is false.
In Python use the if statement like "a=True, if a: print it is true"
For loop can be used to iterate over a list.
In While Loop we can execute a set of statements as long as the condition is true.

# Functions

A function is a block of code which only runs when it is called.
You can pass data, known as parameters into a function.
A function can return data as a result.
Functions can be defined using the "def" keyword followed by the function name and argument in parameters.
The keyord "None" represent the absence of value, and it is the default return value for functions that do not explicitly return anything.

# Classes and objects

Class helps to label and organize related collection of functions and attributes.
We use an uppercase letter for class name.

# Python Operators

Operators are used to perform operations on variables and values.

Python divides operators in the following groups:

* Arithmetic Operators
* Assignment Operators
* Comparison Operators
* Logical Operators
* Identity Operators
* Membership Operators
* Bitwise Operators

Arithmetic Operators

Arithmetic operators are used with numeric values to perform common mathematical operations.
* Addition (+)
* Subtraction (-)
* Multplication (*)
* Division (/)
* Modulus (%)
* Exponentiation (**)
* Floor division (//)

Assignment Operators

Assignment operators are used to assign values to variables.

* =               
* +=
* -=
* /=
* %=
* //=
* **=
* &=
* |=
* ^=
* <<=

Comparison operators

Comparison Operators are used to compare two values.

* Equal (==)
* Not equal (!=)
* Greater than >
* Less than <
* Greater than or equal to >=
* Less than or equal <=

Logical operators

Logical operators are used to combine conditional statements.

* "and" Returns a True if both True
* "or" Returns a True if one is True
* "not" Reverse the result, returns False if the result is True

Identity operator

Identity operators are used to compare the objects, not if they are equal, but if they are actually the same object, with the same memory location.

* "is" Returns True if both variable are the same object.
* "is not" Returns True if both variables are not the same object.

Membership operators

Membership operators are used to test if the sequence is presented in an object.

* "in" Returns True if a sequence with specified value is present in an object.
* "not in" Returns True if a sequence with the specified value is not present in an object.

Bitwise operators

Bitwise operators are used to compare binary numbers.

* AND (&) Sets each bit to 1 if the both bits are 1
* OR (|) Sets each bit to 1 if one of two bits is 1
* XOR (^) Sets each bit to 1 if only one of two bits is 1
* NOT (~) Inverts all the bits
* Zero fill left shift (<<) Shift left by pushing zeros in from the right and let the leftmost bits fall off
* Signed right shift (>>) Shift right by pushing copies of the leftmost bit in from the left and let the rightmost bits fall off

Operator Precedence

Precedence order staring with the highest precedence 

* Parantheses ()
* Exponentiation **
* Unary plus (+x), Unary minus (-x)and Bitwise NOT (~X)
* Multiplication (*), Division (/), Floor division (//) and Modulus (%)
* Addition (+) and Subtraction (-)
* Bitwise left (<<) and right shift (>>)
* Bitwise AND (&)
* Bitwise XOR (^)
* Bitwise OR (|)
* Comparison Operator ( ==, !=, >, >=, <, <=)
* Identity Operators ( is, is not)
* Membership Operators ( in, not in)
* Logal NOT (not)
* AND (and)
* OR (or)

# Ints and Floats

Ints and floats are the two fundamental number types in Python.
Lets see how to convert between them:

This is how division with ints returns a float, 20 divided by 4 gives us 5.0.
Python automatically returns a float to accomodate non-whole numbers.
Adding a float to an int or multiplying or using exponents with both also returns a float.
int is a built-in class in Python, along with other types like string, floats, and list.
Converting one type to another, we call it Casting.
Python does not round when casting floats to ints, it removes the decimal part.
To round a float to the nearest int, we can use the round function.
One pitfall of floats is that they are approximations, which results to rounding errors.
Floata are stored as binary ones and zeros in memory, and due to limited memory, Python makes approximations, leading to these rounding errors.
Using the round function mitigates this issue.



  







