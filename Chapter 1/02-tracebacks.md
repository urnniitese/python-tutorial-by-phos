# Tracebacks

Python prints a traceback in your console when an exception is raised in your code. This might be overwhelming if you are seeing this for the first time, but the Python traceback has a wealth of information that can help you to fix the reason for the exception being raised in your code.

```python
print(Hello)
```

When you run this program above, you'll get the following traceback:

```python
Traceback (most recent call last):
  File "C:\some\path\main.py", line 1, in <module>
    print(Hello)
NameError: name 'Hello' is not defined
```

Try to understand this error line by line. Read tracebacks from the bottom to top.

```python
NameError: name 'Hello' is not defined
```

`NameError` is the exception name. After the exception name is the error message. This message usually contains helpful information for understanding the reason for the exception being raised.

```python
  File "C:\some\path\main.py", line 1, in <module>
    print(Hello)
```

Further up the traceback are the various function calls moving from bottom to top, most recent to least recent. These calls are usually represented by two-line entries for each call. The first line of each call contains information like the path to the file, line number and the module name, all specifying where the code can be found. The second line for these calls contains the actual code that was executed.
