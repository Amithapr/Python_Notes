# # Python Varibales and Data Types # #

# 1.what is variable in python?
    A variable is a name used to store data in a program.
    Note: (In python we do not need to declare variable type it identifies the data type based on the value assigned.)

# Python example:

    name="Amitha"
    age=28
    salary=25000

# How to create a variable?
    we can create a variable by assigning a value using the assignment operator(=)

# syntax:
    variable_name = value

# Example:
    City = "Banglore"
    Age = 28
    Percentage = 80.5

# Rules for naming varibles

    1. A variable name must start with letter or underscore(_)
    2. It connot start with a number.
    3. Variable names can contain letters, numbers and underscores.
    4. Spaces are not allowed in variable names.
    5. Python key words cannot be used as variable names.
    6. Variable names are case sensitive.

# Valid variable names:
    name = "Amitha"
    age = 28
    employee_id = 101
    _salary = 300000

# Invalid Variable names:

    2name ="amitha" (cannot start with number)
    employee name= "amitha" (Spaces are not allowed)
    class="python" ( class is a keyword)

# Data Types#

# what are date types in python?
    A data type defines the type of value stored in a variable.
 
 Python provides different built-in data types to store different kinds of information.
 1) Numeric Data Types: it is used to store numbers.
    
 2) Integer(int): it stores whole numbers without decimal points.

   # Python:
    age=28
    quantity=100
    print(age)
    print(type(age))

# Output
      28
      <class 'int'>>
      
3) Float(float): A float stores numbers containing decimal points.
   
# Python
    price = 99.50
    percentage = 85.75

    print(price)
    print(percentage)

  # output
     99.50
     <class 'float'>

4) Complex (complex): A complex number contains a real part and an imaginary part

# Python
      number = 5 + 3j
    
      print(number)
      print(type(number))

     # output
     (5+3j)
     <class 'complex'>
     
5) String(str): A string is a sequence of characters enclosed within single quotes, double quotes or triple quotes.
    strings are used to store text.

# Python
    name ="Amitha"
    city= "Bangalore"

    print(name)
    print(type(name))
# Output
    Amitha
    <class 'str'>

6)Boolean (bool): Boolean data types store only two values: True or False.
     They are commonly used in conditional statements and decision-making.

# Python
    is_employed = True
    is_married = False

    print(is_employed)
    print(type(is_employed))

# Output
    True
    <class 'bool'>
    
 

