---
title: what-is-the-map-function-in-python
date: 2022-03-13 20:34
---

[Knowledge](Knowledge.md)

# What is the Map Function in Python?

It's a built-in higher-order function that takes a function and a list as
parameters and returns an object that can be turned into a new list with the
function applied to each element of the list.

```python
numbers_list = [1, 2, 3, 4, 5]

def add_one(x):
    return x + 1

# The map function applies the add_one function to each element of the list.
new_numbers_list = list(map(add_one, numbers_list))
```

-   [python](python.md)
-   [what-is-a-higher-order-function](what-is-a-higher-order-function.md)
