## Built-in Data Types in Python

Python offers a variety of built-in data types to represent different kinds of information. Here's an overview of some of the common data types:

### Booleans

- `bool`: A boolean value that can be either `True` or `False`.
  - Logical operations like `and`, `or`, and `not` can be performed on booleans.
  - Examples:
    ```python
    x = True
    y = False
    result = x or y  # If x is False, then y; otherwise x
    ```

### Numbers

- `int`: Integer numbers.
  - Examples:
    ```python
    a = 2
    b = 100
    c = 123456789
    d = 38563846326424324
    ```
  - Integers in Python have arbitrary sizes.

- `float`: Floating-point numbers. Precision depends on the implementation and system architecture.
  - Examples:
    ```python
    a = 2.0
    b = 100.0
    c = 123456789.0
    ```

- `complex`: Complex numbers represented as `a + bj`, where `a` and `b` are real numbers, and `j` represents the imaginary unit.
  - Examples:
    ```python
    a = 2 + 1j
    b = 100 + 10j
    ```

### Type Relationships

In Python 2.x and 3.x, a boolean value is also considered an integer. The `bool` type is a subclass of the `int` type, and `True` and `False` are instances of `bool`.

```python
issubclass(bool, int)  # True
isinstance(True, bool)  # True
isinstance(False, bool)  # True
```

### Complex Numbers and Comparison

Keep in mind that comparison operators like `<`, `<=`, `>`, and `>=` will raise a `TypeError` exception when any operand is a complex number.

These built-in data types serve as fundamental building blocks for various operations and computations in Python.
## Strings, Sequences, and Collections in Python

Python provides various built-in data types to work with different kinds of data. Here's an overview of strings, sequences, and collections:

### Strings

In Python 3.x and 2.x:

- `str`: Unicode strings (in Python 3) or byte strings (in Python 2).
- `bytes`: Byte strings.
- `unicode` (Python 2 only): Unicode strings.

### Sequences and Collections

Python differentiates between ordered sequences and unordered collections like sets and dictionaries.

**Sequences:**

- Strings (`str`, `bytes`, `unicode`) are sequences.
- `reversed`: A reversed order of a sequence.
  ```python
  a = reversed('hello')
  ```
- `tuple`: An ordered collection of values of any type.
  ```python
  a = (1, 2, 3)
  b = ('a', 1, 'python', (1, 2))
  ```
  - Supports indexing.
  - Immutable and hashable if all members are hashable.

- `list`: An ordered collection of values.
  ```python
  a = [1, 2, 3]
  b = ['a', 1, 'python', (1, 2), [1, 2]]
  ```
  - Supports indexing.
  - Mutable but not hashable.

**Collections:**

- `set`: An unordered collection of unique values.
  ```python
  a = {1, 2, 'a'}
  ```

- `dict`: An unordered collection of unique key-value pairs.
  ```python
  a = {1: 'one', 2: 'two'}
  b = {'a': [1, 2, 3], 'b': 'a string'}
  ```
  - Keys must be hashable.

An object is hashable if it has a hash value that remains constant throughout its lifetime (requiring a `__hash__()` method), and it can be compared to other objects (requiring an `__eq__()` method). Hashable objects that compare for equality must have the same hash value.

These data types provide the foundation for working with different kinds of data structures and performing various operations in Python.

[[3.1 - Python - Data Types - Simplified]]
[[3.2 - Python - Data Types - constant built in]]
[[3.3 - Python - Data Types - Testing the Type of Variables]]
[[3.4 - Python - Data Types - Converting Between Data Types]]
[[3.5 - Python - Data Types - Explicit String Types at Definition of Literals]]
[[3.6 - Python - Data Types - Mutable and Immutable Data Types]]
[[3.7 - Python - Data Types - Collection Types]]