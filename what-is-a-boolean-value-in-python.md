---
title: What is a boolean value in python?
date: 2024-01-06
tags: [extract,python,boolean,if]
---

# What is a boolean value in python?
When you evaluate any expression in Python, you will get a boolean value. It's a
value that only can be True or False.

```python
a = 10 > 9
b = 10 == 9
c = 10 < 9

# It will print True
print(a)

# It will print False
print(b)

# It will print False
print(c)
```

When you run a condition in an if statement, Python returns `True` or `False`.

```python
a = 200
b = 33

# Print a message based on whether the condition is True or False
if b > a:
    print("b is greater than a")
else:
    print("b is not greater than a")
```
