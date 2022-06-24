---
title: what-is-a-lambda-function-in-python
date: 2022-03-13 23:11
---

[Knowledge](Knowledge.md)

# What is a Lambda Function in Python?

It's a function that is defined without a name, it takes n number of arguments,
is restricted to a single expression and returns a value.

```python
numbers_list = [1, 2, 3, 4, 5]

# add_one is the name of the variable that holds the lambda function.
add_one = lambda x: x + 1

for number in numbers_list:
    print(add_one(number))
```

-   [python](python.md)
