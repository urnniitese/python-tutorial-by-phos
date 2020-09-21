# Strings

If you want to use text in Python, you have to use a string.
Create a string by using text between two single or double quotation marks.

```python
print("I like double quotation marks")
print('I prefer single quotation marks')
```

> Using `"` or `'` doesn't affect the behavior of the string in any way.

# Backslashes

Some characters can't be directly included in a string.

Here is an example:

```python
print('Joe's mama is nice')
```
```python
File "main.py", line 1
  print('Joe's mama is nice')
             ^
SyntaxError: invalid syntax
```

Characters like these must be escaped by placing a backslash before them.

```python
print('Joe\'s mama is nice')
```

# Newlines

`\n` represents a new line.

```python
print("One\nTwo\nThree")
```

String literals can span multiple lines. One way is using triple-quotes (`"""..."""`) or (`'''...'''`). Newlines are automatically included in a triple-quote string, but you can prevent it by adding a `\` at the end of the line.

```python
print("""\
One
Two
Three
""")

print('''\
One
Two
Three
''')
```

# Raw strings

If you don't want to characters prefaced by `\` to be interpreted as special characters, you can use raw strings by adding an `r` before the first quotation mark.

```python
print('C:\some\name')  # Here \n means newline

print(r'C:\some\name')  # Note the r before the string
```

# Concatenation

You can add strings together using a process called `concatenation`.

```python
print("My name is " + 'Joe')
```

Two or more string literals next to each other are automatically concatenated. However this isn't recommended, except if you are breaking strings.

```python
print("My " "name " "is " "Joe")

print("My name "
      "is Joe")
```

When concatenating strings, it doesn't matter whether they've been created with single or double quotes.

Even if your string contains numbers, they are still added as strings rather than integers.

Adding a string to a number will raise an error.

```python
print("4" + 10)
```
```python
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    print("4" + 10)
TypeError: can only concatenate str (not "int") to str
```

Strings can also be multiplied by integers.

```python
print("xd" * 8)
```
