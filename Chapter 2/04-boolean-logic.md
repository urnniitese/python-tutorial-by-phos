# Boolean logic

Boolean logic is used to make more complicated conditions.

Pythons Boolean operators are `and`, `or` and `not`.

The `and` operator returns **True** if both two arguments are **True**.

```python
print(1 == 1 and 3 == 3) # True

print(6 == 6 and 6 == 9) # False

print(2 != 2 and 4 == 4) # False

print(8 < 7 and 10 > 3) # False
```

The `or` operator return **True** if either (or both) of its arguments are **True**.

```python
print(1 == 1 or 3 == 3) # True

print(6 == 6 or 6 == 9) # True

print(2 != 2 or 4 == 4) # True

print(8 < 7 or 10 < 3) # False
```

> Besides values, you can also compare variables.

Unlike other operators, `not` only takes one argument and inverts it.

The result of `not True` is **False** and `not False` is **True**.

```python
print(not 1 == 1) # False

print(not 1 > 7) # True
```

> You can also nest multiple conditional statements in if statements using the Boolean operators.
