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
>>>
