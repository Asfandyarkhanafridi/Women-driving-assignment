# Data Science:
Describe data science. To discover the hidden actionable insights in an organization's data, data scientists mix math and statistics, specialised programming, sophisticated analytics, artificial intelligence (AI), and machine learning with specialised subject matter expertise. Strategic planning and decision-making can be guided by these findings. The research area of data science is centred on methods and formulas for deriving knowledge from data. The field blends domain-specific data with data mining and machine learning. Before moving on to any complex topics, this section focuses on defining "data". Standard Python Syntax
# Python Syntax:
This is a simple Python programme that prints the phrase "Asfand Afridi!" to the console using the print() method. When learning a new programming language, it's frequently utilised as a straightforward starting point. print("Asfand Afrid!")
# Variables and data types
This programme shows how to create variables in Python and give them various data types. The name variable, age variable, is_male variable, and height variable are all strings, integers, booleans, respectively.

Functions A=5 B=3 print(A+B) = 8 This programme defines a function called square, which multiplies an input number by itself and outputs the result. The function is then called with the parameter of 5, and the result variable is then used to store the function's return value. Finally, the print() method is used to print the value of the result to the console.

def square(x=5): print 25 to represent the square of five.

When defining a function in Python, you have the option of including a third parameter.

# Data Types

There are a number of data types available in Python programming that can be used to store various kinds of values. The most typical data kinds are as follows:

Types of numbers: x = 42, int = 3,14, float = 1, 2j, complex

is_true = True and is_false = False are Boolean types.

List type my_list = [1, 2, 3, 'four', 5.0]

Tuple my_tuple = (1, 2, 3, 'four', 5.0)

Dictionary entry for "name: John," "age: 30," and "city: New York"

My_set's set type is 1, 2, 3, 4, and 5. Len(), append(), remove(), and many other built-in functions and techniques are available in Python for working with various data types.
# A CSV file
Using the csv module in Python, you may read and write CSV files. In addition to comma-separated values (CSV), tab-separated values (TSV), and other delimiter-separated values, the csv module offers capability for working with CSV files in a number of different formats.

Python's csv.reader() function can be used to read a CSV file. The reader object that is returned by this function, which accepts a file object as input, can be used to loop through the CSV file's rows. Here's an illustration:
bring in csv
with file=open('example.csv', 'r'): for each row in reader where reader = csv.reader(file) print(row)
# NumPay
The cornerstone Python module for numerical computing is called Numpy. It offers strong tools for creating, storing, and/or manipulating data, enabling it to easily

# Import
when we want to utilize a library in our Python code, we use the "import" keyword. In the case of the widely used numerical computing library "NumPy," it is conventionally abbreviated as "np" in Python code. Therefore, we can refer to NumPy as "np" after importing it.
import numpy as np
import math
