# else statements

The if statement allows to check if the given condition is **True** to run its indented statements.

However the else statement is used to run statements if the condition of the if statement is **False**.

As with if statements, the code block inside of the else statement should be intended.

```python
a = 5
if a == 6:
  print("Yes")
else:
  print("No")
```

> Don't forget the colon at the end of the else statement.

Every if statement can only have one else statement.
In order to make multiple checks, you can nest if and else statements.

```python
a = 3
if a == 1:
  print("One")
else:
  if a == 2:
    print("Two")
  else:
    if a == 3:
      print("Three")
    else:
      print("Something else")
```

But multiple if and else statements make the code very long and unreadable.
The `elif` statement is a shortcut that is preferably used when nesting if and else statements.

```python
a = 3
if a == 1:
  print("One")
elif a == 2:
  print("Two")
elif a == 3:
  print("Three")
else:
  print("Something else")
```

> The `elif` statement is equivalent to and if/else statement.
