1. What Are Python Keywords?
   Python keywords are reserved words that have special meanings in the Python programming language. They are used to define the syntax and structure of a program.

Keywords cannot be used as ordinary variable names.

2. Common Python Keywords

Keyword	Purpose

1. if	Checks a condition
2. else	Executes an alternative block
3. elif	Checks another condition
4. for	Repeats statements over a sequence
5. while	Repeats statements while a condition is true
6. break	Terminates a loop
7. continue	Skips to the next loop iteration
8. pass	Acts as a placeholder
9. def	Defines a function
10. return	Returns a value from a function
11. class	Defines a class
12. import	Imports a module
13. from	Imports specific names from a module
14. True	Represents a Boolean true value
15. False	Represents a Boolean false value
16. None	Represents the absence of a value
17. and	Logical AND
18. or	Logical OR
19. not	Logical NOT
20. in	Checks membership
21. is	Checks object identity
22. try	Starts exception-handling code
23. except	Handles an exception
24. finally	Runs cleanup code
25. with	Manages a context, such as opening a file
26. as	Assigns an alias or binds a value
27. lambda	Creates a small anonymous function
28. global	Refers to a global variable
29. nonlocal	Refers to a variable in an enclosing function
30. assert	Checks a condition and raises an error if it fails
31. del	Deletes a reference or item
32. yield	Produces a value from a generator
33. async	Defines asynchronous code
34. await	Waits for an asynchronous operation



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
