# while loops

A while loop is used to repeat a block of code while a condition holds.

The structure of a while loop looks like this:

```python
while expression:
  statements
```

Below is a while loop containing a variable that counts up from 1 to 5, at which point the loop terminates.

```python
i = 1
while i <= 5:
   print(i)
   i += 1

print("Finished!")
```

> The code block inside of a while loop is executed repeatedly. This is called iteration.

During each loop iteration, the i variable will get incremented by one (`i += 1`), until it reaches 5.
So, the loop will execute the print function 5 times.

The code below uses an if/else statement inside a while loop to separate the even and odd numbers from 1 to 10:

```python
x = 1
while x < 10:
  if x % 2 == 0:
    print(str(x) + " is even")
  else:
    print(str(x) + " is odd")

  x += 1
```

To end a while loop prematurely, you can use the `break` statement.

```python
i = 0
while True:
  print(i)
  i += 1
  if i >= 5:
    print("Breaking")
    break

print("Finished")
```

> `while True` is a short and easy way to make an infinite loop.

Another statement that can be used within loops is `continue`.
Unlike break, continue jumps back to the top of the loop, rather than stopping it. Basically, the continue statement stops the current iteration and continues with the next one.
