# Simple operations

You can enter simple calculations directly into the `print()` function.

```python
print(2 + 2)
print(5 + 4 - 3)
```

Use parentheses to determine which operations are performed first.

```python
print(2 * (3 + 4))
```

Dividing by zero in Python raises an exception, as no answer can be calculated.

```python
print(11 / 0)
```
```python
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    print(11 / 0)
ZeroDivisionError: division by zero
```

#### Python Arithmetic Operators

Operator | Description | Example | Solution
--- | --- | --- | ---
`*` | Addition | 6 + 16 | 22
`-` | Subtraction | 16 - 6 | 10
`-` | Multiplication | 6 * 16 | 96
`/` | Division | 12 / 6 | 2
`%` | Modulus | 12 % 7 | 5
`//` | Floor division | 9 // 2 | 4
