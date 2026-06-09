> print("vandana")
vandana
>>> name=input("enter your name")
enter your namechetna
>>> age=input("enter your age")
enter your age23
>>> print("my name is",name")
  File "<python-input-13>", line 1
    print("my name is",name")
                           ^
SyntaxError: unterminated string literal (detected at line 1)
>>>  print("my name is",name)
  File "<python-input-14>", line 1
    print("my name is",name)
IndentationError: unexpected indent
>>> print("myself",name);
myself chetna
>>> print("my name is",name);
my name is chetna
>>> print("I am ",age);
I am  23
>>> print("i am",age,"year old");
i am 23 year old
>>> a=10
>>> b=5.5
>>> c="Python"
>>> d= true
Traceback (most recent call last):
  File "<python-input-22>", line 1, in <module>
    d= true
       ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> a=10
>>> b=5.5
>>> c="python"
>>> print(type(a));
<class 'int'>
>>> print(type(b));
<class 'float'>
>>> print(type(c));
<class 'str'>
>>> d=true
Traceback (most recent call last):
  File "<python-input-29>", line 1, in <module>
    d=true
      ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> d=true;
Traceback (most recent call last):
  File "<python-input-30>", line 1, in <module>
    d=true;
      ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> d= True
>>> print(type(d));
<class 'bool'>
>>> num1=float(input("enter first number:"))
enter first number:10
>>> num2=float(input("enter second number:"))
enter second number:20
>>> print("Addition=",num1+num2);
Addition= 30.0
>>> print("subtraction=",num2-num1);
subtraction= 10.0
>>> (print("multiplication=",num1*num2);
  File "<python-input-38>", line 1
    (print("multiplication=",num1*num2);
                                       ^
SyntaxError: invalid syntax
>>> (print("multiplication=", num1 * num2 );
  File "<python-input-39>", line 1
    (print("multiplication=", num1 * num2 );
                                           ^
SyntaxError: invalid syntax
>>> (print("multiplication=", num1 * num2 )
... (print("multiplication=", num1 * num2 )(print("multiplication=", num1 * num2 )(print("multiplication=", num1 * num2 )
... >>> num1=float(input("enter first number:"))
... enter first number:10
... >>> num2=float(input("enter second number:"))
... enter second number:20
... p
...
  File "<python-input-40>", line 2
    (print("multiplication=", num1 * num2 )(print("multiplication=", num1 * num2 )(print("multiplication=", num1 * num2 )
                                                                                  ^
SyntaxError: '(' was never closed
>>> (print("multiplication=",num1*num2);
  File "<python-input-41>", line 1
    (print("multiplication=",num1*num2);
                                       ^
SyntaxError: invalid syntax
>>> (print("multiplication=",num1 * num2);
  File "<python-input-42>", line 1
    (print("multiplication=",num1 * num2);
                                         ^
SyntaxError: invalid syntax
>>>
>>> print("multiplication=",num1*num2);
multiplication= 200.0
>>> print(division=",num1/num2);
  File "<python-input-45>", line 1
    print(division=",num1/num2);
                   ^
SyntaxError: unterminated string literal (detected at line 1)
>>> print("division=",num1/num2);
division= 0.5
>>> weight = float(input("Enter your weight in kg: "))
Enter your weight in kg: 86
>>> height = float(input("Enter your height in meters: "))
...
Enter your height in meters: 180
>>> bmi = weight / (height ** 2)
>>> print(f"Your BMI is: {bmi:.2f}");
Your BMI is: 0.00
>>> if bmi < 18.5:
...      category = "Underweight"
...      elif 18.5 <= bmi < 24.9:
...           category = "Normal weight"
...           elif 25 <= bmi < 29.9:
...                  category = "Overweight"
...                  else:
...                       category = "Obese"
...                       print(f"You are classified as: {category}")
...
 celsius = float(input("Enter temperature in Celsius: "))
Enter temperature in Celsius: 43
>>> fahrenheit = (celsius * 9/5) + 32
>>> print(f"{celsius}°C is equal to {fahrenheit}°F");
43.0°C is equal to 109.4°F
>>>

