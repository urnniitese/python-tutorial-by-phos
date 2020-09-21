# Input

To receive input from the user in Python you can use the `input()` function.
This function prompts the user for input in your console and always returns the input as a string. Means if the input is `7`, it will be converted to `"7"`.

```python
x = input()
print(x)
```

You can also add a prompt message to the `input()` function.

```python
name = input("Enter your name: ")
print("Nice to meet you, " + name)
```

To convert the input to a number you can use the `int()` function.

```python
age = int(input("Enter your age: "))
print(age)
```

You can also convert a number to a string using the `str()` function.

```python
age = 18
print("Joe is " + str(age) + " old, impressive!")
```

You can convert to floats as well using the `float()` function.

When executing the `input()` function the program flow stops until the user enters some value.

```python
name = input("Enter your name: ")
age = input("Enter your age: ")

print(name + " is " age + " years old.")
```
