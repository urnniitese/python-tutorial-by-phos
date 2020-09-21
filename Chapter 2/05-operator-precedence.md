# Operator precedence

Operator precedence is a very important concept in programming.
Such as multiplication being performed before addition in mathematics, the Boolean logic extends this order of operations.

```python
print(False == False or True) # True

print(False == (False or True)) # False

print((False == False) or True) # True
```

> Pythons order of operations is the same as normal mathematics: Parentheses first, then exponentiation, then multiplication/division, then addition/subtraction.

# Chaining multiple conditions

You can chain conditional statements in an if statement using the Boolean operators.

```python
age = 66
if age >= 50 and age <= 100:
  print("You passed!")
```
