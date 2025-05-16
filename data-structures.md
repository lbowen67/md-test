Python includes several **built-in data structures** that allow you to store multiple items within a single variable. They are designed to handle collections of data efficiently, each with its own characteristics and use cases. These structures are versatile and can hold various data types, including integers, strings, floats, booleans, other collections, and even custom objects. The following are a few of the most common in Python:

###List (list)

**Definition:** An ordered, mutable collection that allows duplicate elements.

**Key Features:**
- Ordered: Maintains the insertion order of elements.
- Mutable: Elements can be added, removed, or changed.
- Allows Duplicates: Can contain multiple instances of the same value.
- Indexable: Elements can be accessed using indices.
- Syntax: Defined using square brackets [].

**Example: Managing a shopping list where items can be added, removed, or modified.**
```
shopping_list = ['milk', 'eggs', 'bread']
shopping_list.append('butter')
print(shopping_list)  # Output: ['milk', 'eggs', 'bread', 'butter']
```

###Tuple (tuple)

**Definition:** An ordered, immutable collection that allows duplicate elements.

**Key Features:**
- Ordered: Maintains the insertion order of elements.
- Immutable: Once created, elements cannot be modified.
- Allows Duplicates: Can contain multiple instances of the same value.
- Indexable: Elements can be accessed using indices.
- Syntax: Defined using parentheses ().

**Example: Storing geographical coordinates.**
```
coordinates = (32.1450° N, -80.7560° W)  # Latitude and Longitude
print(coordinates)  # Output: (32.1450° N, -80.7560° W)
```

###Set (set)

**Definition:** An unordered, mutable collection of unique elements.

**Key Features:**

- Unordered: Does not maintain the insertion order of elements.
- Mutable: Elements can be added or removed.
- Unique Elements: Automatically removes duplicate values.
- Non-Indexable: Elements cannot be accessed using indices.
- Syntax: Defined using curly braces {} with elements separated by commas.

**Example: Identifying unique fruits from a list.**
```
fruits = ['apple', 'banana', 'apple', 'orange']
unique_fruits = set(fruits)
print(unique_fruits)  # Output: {'banana', 'orange', 'apple'}
```
###Dictionary (dict)

**Definition:** An ordered (as of Python 3.7), mutable collection of key-value pairs.

**Key Features:**

- Ordered: Maintains the insertion order of key-value pairs.
- Mutable: Key-value pairs can be added, removed, or changed.
- Unique Keys: Keys must be unique; values can be duplicated.
- Key-Based Access: Values are accessed using their corresponding keys.
- Syntax: Defined using curly braces {} with key-value pairs separated by colons.

**Example: Storing a person's contact information.**
```
contact_info = {
    'name': 'Alice',
    'email': 'alice@example.com',
    'phone': '555-1234'
}
print(contact_info['email'])  # Output: alice@example.com
```
