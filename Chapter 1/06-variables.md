# Variables

A variable allows you to store a value by assigning it to a name. This variable can be used to refer to the value later in your program.

To assign a variable, use the equals sign character (`=`).

```python
username = "Joe"
```

You can now use the `username` variable to perform corresponding operations.

```python
print(username)

print(username * 3)
```

You can also reassign the value of this variable as many times as you want.

In Python you don't need to define the type of the variable.

In Python you don't need to declare variables before using them, or declare their type. Every variable in Python is an object.

To avoid mistakes, try to avoid overwriting the same variable with different data types.

# Variable names

Certain restrictions apply in regard to the characters that may be used in variable names.

The only characters that are allowed are letters, numbers and underscores. Additionally they can't start with numbers.

```python
wEiRd_777_NAME_butALLOWED = 7

123ABC = 7
```
```python
File "main.py", line 1
  123ABC = 7
     ^
SyntaxError: invalid syntax
```

You can also remove a variable using the `del` statement.

```python
a = 5
del a
print(a)
```
```python
Traceback (most recent call last):
  File "main.py", line 3, in <module>
    print(a)
NameError: name 'a' is not defined
```
