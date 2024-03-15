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

# BASIC DATA TYPES
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
Floats are stored as binary ones and zeros in memory, and due to limited memory, Python makes approximations, leading to these rounding errors.
Using the round function mitigates this issue.

# Boolean

Python easily casts intergers to booleans.
1 is True and 0 is False.
Even -1 and imaginary 1 are True.
Float 0 and imaginery 0 are false.
We can cast data structures to booleans as well. An empty list or dictionary is false, but anything inside is True.

# Strings

Python has numerous tools to analyze and construct strings, and one of the most useful is slicing.
Slicing refers to taking a portion of a string and returning it.
F-String allow us to insert variables or expressions inside curly braces in a string.
We can also do roundng and number formatting with f-strings.

# Bytes 

It is used behind the scenes in programs.
It is data that is passed around but rarely modified directly.
Computer stores information as ones and zeros.
Bytes objects is commonly used for streaming files or transmitting text without knowing the encoding.
Decode function can be used to turn a byte object back into string.
Bytes objects are immutable, but you can use a byte array if you need to modify the data.

# BASIC DATA STRUCTURES

# Lists

Lists are used to store multiple items in a single variable.
Lists can be created using square brackets.
List items are ordered, changeable, and allow duplicate values.
List items are indexed, the first item has index [0], the second item has index [1] etc.
To determine how many items a list has, use len() function.
List item can be any data type, e.g String, int and boolean.
To add an item to the end of the list we can use the append() method.
If you want to insert an item a specific position in the list, we can use insert() method.
To remove an item based on its value not index, use the remove() method.
pop() method removes and returns the items at the end of the list.
To remove all items in a list we can use a loop with pop().
To make a copy of a list,we can use the copy() method.

# Tuples and Sets

Tuples are used to store multiple items in a single variable.
A tuple is a collecton which is ordered, unchangeable and allow duplicate values.
Tuples are written with round brackets.
To determine how many items a tuple has, use the len() function.
To create a tuple with only one letter, you have to add a comma after the item.
Tuple items can be any data type, such as String, int and boolean.
Tuples are defined as objects with the data type 'tuple'.
You can use a tuple() constructor to make a tuple.
Sets are defined using curly brackets.
Sets are used to store multiple items in a single variable.
A set is collection which is unordered, unchangeable and unindexed.
Use of sets in programming is to remove duplicates from a list, since sets only contains unique values.
You can add elements in a set using add() function and remove elements using the discard() function.

# Dictionaries

Dictionaries are used to store values in key:value pairs.
A dictionary is a collection which is ordered, changeable and do not allow duplicate.
Dictionaries are written with curly brackets, and have keys and values.
To determine how many items in a dictionary use a len() function.
The values in a dictionary can be any data type.
Dictionaries are defined as objects with the data type 'dict'.
You can use a dict() constructor to make a dictionary.
You can acces keys and values of a dictionary using the .keys() and .values() method.

# List comprehension

List comprehension is a special feature in python that sets it apart from other programming languages.
Using a  list comprehension, we multiply each item in the list by two.
The list comprehension is enclosed in square brackets.
It allows you to create a for loop in one line while also returning a copy of the list you are iterating over.
It also enables you to filter or apply functions to every item in a list.
"split" is a new string function, it allows you to split strings based on a given character or string.
"cleanWord" function



  







