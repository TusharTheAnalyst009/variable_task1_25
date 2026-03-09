# variable_task1_25

## Python Data Types and Type Conversion

  * Created Variables

In Python, variables can store different types of data.

a = 2
b = "2"

Here:

a stores a number → Integer

b stores a value inside quotes → String

* Printing Variables
print("a =", a)
print("b =", b)

Output:

a = 2
b = 2

Even though both values look the same, their data types are different.

* Checking Data Types

We use the type() function to check the data type of a variable.

print("a =", a, type(a))
print("b =", b, type(b))

Output:

a = 2 <class 'int'>
b = 2 <class 'str'>

Explanation:

a → int (integer)

b → str (string)

* Error When Adding Different Data Types

If we try to add an integer and a string, Python gives an error.

Example:

print(a + b)

Error:

TypeError: unsupported operand type(s) for +: 'int' and 'str'

Reason:
Python cannot directly add integer and string values.

* Type Conversion (Casting)

We can convert data types using functions like int() and str().

Convert String to Integer
print(a + int(b))

Output:

4

Here:

"2" → converted to integer 2

Convert Integer to String
print(str(a) + b)

Output:

22

Here:

2 → converted to string "2"

"2" + "2" → becomes "22"

6. Program Flow Example
print("started")

print(a + int(b))

print(str(a) + b)

print("ended")

Output:

started
4
22
