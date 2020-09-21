# List operations

Items in lists can be reassigned using the indexing.

```python
nums = [7, 7, 7, 7, 7]
nums[2] = 5
print(nums)
```

Lists can be added and multiplied, similar to strings.

```python
nums = [1, 2, 3]
print(nums + [4, 5, 6])
print(nums * 3)
```

To check if an item is in a list, the `in` operator can be used.
It returns **True** if the item is at least one time in the list, and **False** if not.

```python
words = ["spam", "egg", "spam", "sausage"]
print("spam" in words)
print("egg" in words)
print("tomato" in words)
```

> The in operator is also used to determine whether or not a string is a substring of another string.

To check if an item isn't in a list, the `not` operator can be used.

```python
nums = [1, 2, 3]
print(not 4 in nums)
print(4 not in nums)
print(not 3 in nums)
print(3 not in nums)
```
