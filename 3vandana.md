 def is_palindrome(number):
...     num_str = str(number)
...     return num_str == num_str[::-1]
... print (is_palindrome(121))
...
True
>>> print(is_palindrome(123))
False
>>>
 def fibonacci(n):
...     if n == 0:
...         return 0
...     elif n == 1:
...         return 1
...     return fibonacci(n - 1) + fibonacci(n - 2)
...
... for i in range(10):
...     print(fibonacci(i), end=" ")
...
0 1 1 2 3 5 8 13 21 34 >>>

>>> def add(a, b):
...     return a + b
...     print(add(10,5))
...
>>>
>>> def add(a, b):
...     return a + b
...     print(add(10, 5))
...
>>> def add(a, b):
...     return a + b
...
... def subtract(a, b):
...     return a - b
...
... def multiply(a, b):
...     return a * b
...
... def square(n):
...     return n * n
...
... def factorial(n):
...     if n == 0 or n == 1:
...         return 1
...
...     result = 1
...     for i in range(2, n + 1):
...         result *= i
...
...     return result
...
...
... print("Addition:", add(10, 5))
... print("Subtraction:", subtract(10, 5))
... print("Multiplication:", multiply(10, 5))
... print("Square:", square(6))
... print("Factorial:", factorial(5))
...
Addition: 15
Subtraction: 5
Multiplication: 50
Square: 36
Factorial: 120
