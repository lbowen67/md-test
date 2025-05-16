The following are a list of **Common Operations:**

|Operation|Example|Description|
|:--------:|:-----------:|:-------:|:------:|
|Indexing|	fruits[1]|	Get item at index 1|
|Slicing|	fruits[1:3]|	Get sublist from index 1 to 2|
|Append	|fruits.append("grape")|	Add item to end|
|Insert	|fruits.insert(1, "kiwi")|	Insert at specific position|
|Remove	|fruits.remove("apple")	|Remove first occurrence|
|Pop|	fruits.pop()|	Remove and return last item|
|Length	|len(fruits)|	Get number of items|
|Sort|	fruits.sort()|	Sort list in place|
|Reverse|	fruits.reverse()|	Reverse the order|

```python3.run
fruits = ["apple", "banana", "cherry", "orange"]
print(fruits)
print()

# Indexing
print(fruits[1])
print()

# Slicing
slice = fruits[1:3]
print(slice)
print()

# Append
fruits.append("grape")
print(fruits)
print()

# Insert
fruits.insert(1, "kiwi")
print(fruits)
print()

# Remove
fruits.remove("apple")
print(fruits)
print()

# Pop
fruits.pop()
print(fruits)
print()

# Length
print(len(fruits))
print()

# Sort
print(fruits)
fruits.sort()
print(fruits)
print()

# Reverse
print(fruits)
fruits.reverse()
print(fruits)
print()
```
