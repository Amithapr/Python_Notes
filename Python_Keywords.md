1. What Are Python Keywords?
   Python keywords are reserved words that have special meanings in the Python programming language. They are used to define the syntax and structure of a program.

Keywords cannot be used as ordinary variable names.

2. Common Python Keywords

Keyword	Purpose
if	Checks a condition
else	Executes an alternative block
elif	Checks another condition
for	Repeats statements over a sequence
while	Repeats statements while a condition is true
break	Terminates a loop
continue	Skips to the next loop iteration
pass	Acts as a placeholder
def	Defines a function
return	Returns a value from a function
class	Defines a class
import	Imports a module
from	Imports specific names from a module
True	Represents a Boolean true value
False	Represents a Boolean false value
None	Represents the absence of a value
and	Logical AND
or	Logical OR
not	Logical NOT
in	Checks membership
is	Checks object identity
try	Starts exception-handling code
except	Handles an exception
finally	Runs cleanup code
with	Manages a context, such as opening a file
as	Assigns an alias or binds a value
lambda	Creates a small anonymous function
global	Refers to a global variable
nonlocal	Refers to a variable in an enclosing function
assert	Checks a condition and raises an error if it fails
del	Deletes a reference or item
yield	Produces a value from a generator
async	Defines asynchronous code
await	Waits for an asynchronous operation

3. Example Program
'''python
age = 25
if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
'''
Output

Eligible to vote

Explanation

* if checks whether the age is at least 18.
* else provides an alternative when the condition is false.
* print() displays the result.

4. Important Points

* Python keywords are case-sensitive.
* if is a keyword, but IF is not the same keyword.
* Keywords cannot be used as ordinary variable names.
* Python’s exact keyword list depends on the Python version.
* Some words, such as print, are built-in functions rather than keywords.

5. How to View the Keyword List

Run this program in Python:

import keyword
print(keyword.kwlist)

This displays the hard keywords recognized by your Python installation.
