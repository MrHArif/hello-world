# hello-world
My first repository as per GitHubDocs Quickstart guide

Brunel Graduate of 2022, Bachelors in Computer Science (Hons. Software Engineering) with Professional Practice.

I am starting my programming journey as a professional (Software Engineer) and will be recording or documenting all the material I have been able to cover.


******************************************************************ProgrammingJournal**********************************************************************

🐍 Python (PY)
Inventor of Python, Guido van Rossum in the early 90s.
Design philosophy focuses on code readability.
In order to use non-ASCII characters, Python requires explicit encoding and decoding of strings into Unicode. In IBM® SPSS® Modeler, Python scripts are assumed to be encoded in UTF-8, which is a standard Unicode encoding that supports non-ASCII characters. The following script will compile because the Python compiler has been set to UTF-8 by SPSS Modeler.
Syntax
Variables
Data types
STRING concatenation.
SYNTAX & more.co
1
Data types
Built-in Data Types
In programming, data type is an important concept.
Variables can store data of different types, and different types can do different things.
Python has the following data types built-in by default, in these categories:

Boolean statements 
❎ “False”, ✅ False
Functions 
📝 Why functions show an error
Example: Function can be considered as a potato processing machine, as long as it is being used to pass potato for processing we are good but if we decided to pass a a rock to the machine(aka function) it would not work and show an error.
Data type error:
nam_char = len(input("Full name: \n"))
print("Your name has " + str(nam_char) + " characters")

Data If we didn’t use the str(nam_char), python would show an error as it cannot concatenate integers to string and that bit of code str() converts nam_char data type to a string so that it can be read by the interpreter and the print function can display the concatenated string. (AKA TYPECASTING)
Syntax for printing Data Type

	Example:

fileName = “ filename ” 
print(type(fileName))

OUTPUT: <class ‘str’>
number = 1 
print(type(number))

OUTPUT: <class ‘int’>

pi = 3.141592653589793 
print(type(pi))

OUTPUT: <class ‘float’>

Mathematical Operators
PEMDAS is a key concept to remember while using mathematical operators and as per the rule it means multiplication happens before division but that’s not the case as they both are equally important.(“The calculations most to the left will be prioritised”)
# PEMDAS
# Parenthese
# Exponents
# Multiplication
# Division
# Addition
# Subtraction

print(3*3+3/3-3)

STEPS OF PYTHON INTERPRETS THE CODE (Thorny)

print(9+3/3-3)
print(9+1.0-3)
print(10.0-3)
print(7.0)
7
….N


Print Statements
					Syntax for printing text and number

print(“ TEXT ”)
print(1)
Syntax for saving LOC







STRINGS
Syntax for STRING index referencing (SUBSCRIPTING)

The index of string starts at 0 and so on (and this is because of binary) 

Syntax for STRING concatenation 

The concatenation operators combine two strings to form one string by appending the second string to the right-hand end of the first string. The concatenation might occur with or without an intervening blank.
input() function
The input() function takes input from the user and returns it.
input(“THE MESSAGE TO PRINT FOR USER —Prompt”)

Parameter Values

The input() function reads a line from the input (usually from the user), converts the line into a string by removing the trailing newline, and returns it.

Caculating the length of input 

Thorny (Debugg current script -> Step Into -> Step into -> ….. -> Step into), it helps understand how to computer breaks down the code and process it step by step.
 len() function
The len() function returns the number of items (length) in an object.
Parameters
The len() function takes a single argument s, which can be
sequence - string, bytes, tuple, list, range OR,
collection - dictionary, set, frozen set
Return Value
len() function returns the number of items of an object.
Failing to pass an argument or passing an invalid argument will raise a TypeError exception.

*Internally, len() calls the object's __len__ method. You can think of len() as:
def len(s):
    return s.__len__()
So, you can assign custom length to the object (if necessary)
Variables

Variable name can contain upper and lower case letters, numbers and the underscore character 
▪ A variable name must start with a letter or the underscore character. A variable name cannot start with a number. 
▪ A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ) Variable names are case-sensitive (age, Age and AGE are three different variables) 
▪ Examples: 
>>> 76trombones = 'big parade' SyntaxError: invalid syntax >>> more@ = 1000000 SyntaxError: invalid syntax 
>>> class = 'Advanced Theoretical Zymurgy' SyntaxError: invalid syntax

Example:
We use the following bit of code:
print(len(input("What is your name")))

We are able to accept the input prompted and are able to measure the length of the input but there is know way of recalling this as the variable is not stored (very similar to writing down a phone number and not putting a name next to it, so there is no way of knowing). However, the code snippet below shows how we can recall the values as we modify and more meaning to code. 
✅ 
inputString = input("Your name >")
lengthOfString = len(inputString)
print("your name has ",lengthOfString)


Syntax for printing variables

	Example:

fileName = “ filename ” 
print(fileName)

OUTPUT: filename

number = 1 
print(number)

OUTPUT: 1
