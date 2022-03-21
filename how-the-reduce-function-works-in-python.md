---
title: how-the-reduce-function-works-in-python
date: 2022-03-20 19:16
---

[Extracts](Extracts.md)

# How the reduce() Function Works in Python

It's a high-order function from the functools module. It operates on any
iterable performing the following steps:

1. Apply a function to a the first two items in an iterable and generate a partial result.
2. Pass the partial result to the function with the next item in the iterable
3. Repeat until the iterable is exhausted and return the final result.

```python
# Import the reduce function from the functools module
from functools import reduce

numbers_list = [1, 2, 3, 4, 5]

# Anonymous function that adds its two arguments
func_add = lambda x, y: x + y

# Pass the func_add function and the numbers_list to the reduce function
total = reduce(func_add, numbers_list)

print(total)
```

-   [pythons reduce from functional to pythonic style](pythons-reduce-from-functional-to-pythonic-style.md)
-   [python](python.md)
-   [functional-programming](functional-programming.md)
