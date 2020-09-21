# if statements

You can use if statements to run a code block if a certain condition holds.

If the expression of the if statement evaluates to **True**, some statements are carried out. Otherwise this code isn't interpreted.

The structure of an if statement looks like this:

```python
if expression:
  statements
```

> Python uses indentation (white space at the beginning of a line) to delimit blocks of code. Depending on the program's logic, indentation can be mandatory. The statements in the if should be indented.

> Don't forget the colon at the end of the expression in the if statement.

Here is a simple example of an if statement:

```python
if 20 > 10:
  print("20 is greater than 10")

print("End of the program")
```

The expression (`20 > 10`) evaluates **True** if 20 is greater than 10. Since this expression is **True**, the indented statement (`print("20 is greater than 10")`) is run.

The unindented statement (`print("End of the program")`) which isn't part of the if statement is run after the code block inside of the if statement.

To perform more complex checks you can nest your if statements.

This is used to check if multiple conditions are **True**.

```python
a = 10
if a > 2:
  print("This number is bigger than 2")
  if a <= 40:
    print("This number is between 2 and 40")
```

> Indentation is used to define the level of nesting.
