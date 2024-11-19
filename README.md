# Python-week-2
This is my 2 assignment for Python built-in structures.

Here are short notes on Python's built-in data structures:

### 1. **List**
- **Definition**: An ordered collection of items that can be changed (mutable).
- **Syntax**: `my_list = [1, 2, 3, 'apple']`
- **Key Operations**:
  - `append()`: Adds an item to the end.
  - `insert()`: Adds an item at a specific index.
  - `remove()`: Removes the first occurrence of an item.
  - `pop()`: Removes and returns an item at a given index.
  - `extend()`: Adds multiple items to the end.
- **Indexing**: Supports negative indexing (`-1` for the last item).

---

### 2. **Tuple**
- **Definition**: An ordered collection of items that is immutable (cannot be changed after creation).
- **Syntax**: `my_tuple = (1, 2, 3, 'apple')`
- **Key Operations**:
  - `count()`: Returns the number of occurrences of a value.
  - `index()`: Returns the index of the first occurrence of a value.
- **Use Case**: Often used for heterogeneous (different types) data and to ensure data integrity by making it immutable.

---

### 3. **Set**
- **Definition**: An unordered collection of unique items.
- **Syntax**: `my_set = {1, 2, 3, 'apple'}`
- **Key Operations**:
  - `add()`: Adds an element to the set.
  - `remove()`: Removes an element, raises an error if not found.
  - `discard()`: Removes an element, does nothing if not found.
  - `union()`, `intersection()`, `difference()`: Set operations to compare and combine sets.
- **Use Case**: Ideal for removing duplicates from a collection or performing mathematical set operations.

---

### 4. **Dictionary**
- **Definition**: An unordered collection of key-value pairs (keys must be unique).
- **Syntax**: `my_dict = {'key1': 'value1', 'key2': 'value2'}`
- **Key Operations**:
  - `get()`: Retrieves a value by key (returns `None` if key is not found).
  - `update()`: Adds or updates key-value pairs.
  - `keys()`: Returns a view of all keys.
  - `values()`: Returns a view of all values.
  - `items()`: Returns a view of key-value pairs.
- **Use Case**: Used for associating unique keys with values (e.g., a phonebook).

---

### 5. **String (Technically not a data structure but a sequence type)**
- **Definition**: An immutable sequence of characters.
- **Syntax**: `my_string = "Hello, World!"`
- **Key Operations**:
  - `len()`: Returns the length of the string.
  - `lower()`, `upper()`: Converts to lowercase or uppercase.
  - `split()`: Splits string into a list based on a delimiter.
  - `join()`: Joins a list of strings into one string.
- **Use Case**: Handling and manipulating textual data.

### Assignment
1. Create an empty list called my_list.
2. Append the following elements to my_list: 10, 20, 30, 40.
3. Insert the value 15 at the second position in the list.
4. Extend my_list with another list: [50, 60, 70].
5. Remove the last element from my_list.
6. Sort my_list in ascending order.
7. Find and print the index of the value 30 in my_list.
