# Assignment--3-
this is my assignment-3


# Task -->1
def factorial(n):
    if n < 2:
        return 1

    else:
        return n * (factorial(n-1))
    
num = int(input("enter a number: "))
result = factorial(num)
print(f"Factorial of {num} is : {result} ")

# Task -->2

import math

def number():
    n = int(input("enter the number: "))
    print("square root :",n ** 0.5)
    print("Logarithm : ", math.log(n))
    print("Sine : ",math.sin(n))

number()
