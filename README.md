##################                task no  1           ###############################################
step 1 :Defining the Function:
def factorial(n):
This defines a function named factorial that takes an input n.

step 2: Base Case of Recursion:
if n < 2:
    return 1
If n is less than 2 (i.e., 0 or 1), the function returns 1.
This is the base case of recursion (to stop further calls).

step 3: Recursive Case:
else:
    return n * (factorial(n-1))
If n is 2 or more, it calls itself with n-1.

For example: factorial(5) becomes 5 * factorial(4), and so on until it reaches factorial(1).

step 4:User Input:
n = int(input('Enter a number:'))
The user is asked to input a number.
The input is converted to an integer and stored in variable n.

step 5:Function Call and Output:
result = factorial(n)
print('factorial of', n, 'is', result)
The factorial() function is called with the user’s input.

.....................................................................................................................................................
###################################              task no 2            ############################################################

1.Importing Math Functions:
from math import *
This imports all mathematical functions like sqrt(), log(), and sin() from the math module.

2.Input from User:
n = int(input("enter any number"))
The program prompts the user to enter a number.
The input is converted to an integer and stored in the variable n.

3.Square Root:
print('square root:', sqrt(n))
This prints the square root of the number using sqrt(n).

4.Logarithm (Natural Log):
print('logarithmic root:', log(n))
This prints the natural logarithm (base e) of the number using log(n).

5.Sine Value:
print('sine:', sin(n))
This prints the sine of the number in radians using sin(n).
