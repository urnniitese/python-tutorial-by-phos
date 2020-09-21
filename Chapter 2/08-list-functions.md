# List functions

The `list.append()` method adds an item to the end of an existing list.

```python
nums = [1, 2, 3]
nums.append(4)
print(nums)
```

> The `.` before append determines that it is a method of the list class.

To get the number of items in a list, you can use the `len()` function.


```python
nums = [1, 3, 5, 2, 4]
print(len(nums))
```

> Unlike the index of the items, `len()` does not start with `0`. So, the list above contains `5` items, meaning `len()` will return `5`.

The `list.insert()` method is similar to `list.append()`, except that it allows you to insert a new item at any position in the list, as opposed to just at the end.

```python
words = ["Joe", "cookies."]
index = 1
words.insert(index, "loves")
print(words)
```

> Elements that are after the inserted item, are shifted to the right.

The `list.index()` method finds the first occurrence of a list item and returns its index.
If the item isn't in the list, the ValueError exception is raised.

```python
letters = ['p', 'q', 'r', 's', 'p', 'u']
print(letters.index('r'))
print(letters.index('p'))
print(letters.index('z'))
```

There are a few more useful functions and methods for lists.

`max(list)`: Returns the list item with the maximum value.

`min(list)`: Returns the list item with minimum value.

`list.count(item)`: Returns a count of how many times an item occurs in a list.

`list.remove(item)`: Removes an object from a list.

`list.reverse()`: Reverses items in a list.
