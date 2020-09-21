# Lists

Lists are used to store items.

You can create a list using square brackets (`[]`) with commas (`,`) separating the items.

```python
fruits = ["apple", "pear", "orange"]
```

The `fruits` list above contains 3 string items.

A certain item in the list can be accessed using the index in square brackets.

```python
fruits = ["apple", "pear", "orange"]
print(fruits[0])
print(fruits[1])
print(fruits[2])
```

> The first list items index is `0`, rather than `1`, as might be expected.

Sometimes you need to create an empty list, it's created with an empty pair of square brackets.

```python
empty_list = []
print(empty_list)
```

Typically, a list contains items of a single type, but it's also possible to include several different types. Additionally lists can be nested.

```python
a = 6
my_list = ["apple", 9, [4, 5, a], 7.9273]
print(my_list[1])
print(my_list[2])
print(my_list[2][2])
```

Nested lists can be used to represent 2D grids, such as matrices.

```python
m = [
    [1, 2, 3],
    [4, 5, 6]
    ]
print(m[1][1])
```

There are some types, such as strings, that can be indexed like lists.
Indexing strings behaves like you are indexing a list containing each character in the string.

```python
sentence = "Joe loves programming."
print(sentence[6])
```

> The space symbol (`" "`) also has an index.

Indexing may also have negative numbers to start counting from the right.

```python
sentence = "Joe loves programming."
print(sentence[-1]) # last character
print(sentence[-2]) # second-last character
print(sentence[-8])
```

> Because `-0` is the same as `0`, negative indexing starts from `-1`.

In addition to indexing you can also slice strings. Slicing allows you to obtain a substring.

```python
sentence = "Joe loves programming."
print(sentence[0:3]) # characters from position 0 (included) to 3 (excluded)
print(sentence[2:8]) # characters from position 2 (included) to 8 (excluded)
```

> Note that the start is always included and the end always excluded.
