# Booleans

The two Boolean values are **True** and **False**.
They can be created by comparing values, for instance by using the equal operator `==`.

```python
a = True
print(a) # True

print(2 == 3) # False

print("hello" == "hello") # True

print("hello" == "Hello") # False
```

Another comparison operator, the not equal operator (`!=`) evaluates to **True** if the values being compared aren't equal and **False** if they are.

```python
print(1 != 1) # False

print("joe" != "Joe") # True

print(2 != 10) # True
```

Python also has an operator that determines whether one number is greater than (`>`) or smaller than (`<`) another.

```python
print(8 > 3) # True

print(7 < 7) # False
```

Additionally there are the greater than or equal (`>=`) and smaller than or equal (`<=`) operators.

They are the same as the strict greater than and smaller than operators, except that they evaluate **True** when comparing equal numbers.

```python
print(7 <= 8) # True

print(10 >= 10.0) # True
```

These operators can also be used to compare strings lexicographically.

```python
print("Jimmy" > "Joe") # True
```
