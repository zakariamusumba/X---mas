Multiply Function
A simple Python function that calculates the product of two numbers, prints the result, and returns it.

Function Signature
python
def calculate(x, y):
    result = x * y
    print(result)
    return result
Description
The calculate function takes two arguments, multiplies them together, prints the product to the console, and returns the result.

Parameters
Parameter	Type	Description
x	int or float	The first number to multiply
y	int or float	The second number to multiply
Returns
Type	Description
int or float	The product of x and y
Usage
Basic Example
python
calculate(3, 4)
Output:

text
12
Storing the Result
python
result = calculate(5, 6)
print(f"Stored result: {result}")
Output:

text
30
Stored result: 30
With Floating Point Numbers
python
calculate(2.5, 4.0)
Output:

text
10.0
With Negative Numbers
python
calculate(-3, 7)
Output:

text
-21
Notes
The function uses the * operator, so it works with any types that support multiplication (e.g., integers, floats, and even strings or lists).

The result is printed and returned, so it can be used both for display and further computation.

Example with Strings
python
calculate("ab", 3)
Output:
