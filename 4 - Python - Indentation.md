****
---

**Simple example**

In Python, the grouping of statements is based on indentation. Guido van Rossum, Python's creator, decided on this approach. You can find the reasons behind this choice in the first section of the "Design and History Python FAQ". Colons, `:`, signal the start of an indented code block. Here's an example:

```python
class ExampleClass:
    # Every function belonging to a class must be indented equally
    def __init__(self):
        self.name = "example"
        
    def someFunction(self, a):
        # Notice everything belonging to a function must be indented
        if a > 5:
            return True
        else:
            return False

# If a function is not indented to the same level, it will not be considered as part of the parent class
def separateFunction(b):
    for i in b:
        # Loops are also indented, and nested conditions start a new indentation
        if i == 1:
            return True
    return False

separateFunction([2, 3, 5, 6, 1])
```

**Spaces or Tabs?**

For indentation, using 4 spaces is recommended. However, both tabs and spaces can be used, provided you use them consistently throughout your code. Mixing tabs and spaces can result in errors in Python 3 and might cause issues in Python 2.

[[4.1 - Python - Indentation - How Indentation Parsed]]
[[4.2 - Python - Indentation - Indentation Error]]