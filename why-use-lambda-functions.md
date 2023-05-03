---
title: Why use lambda functions?
date: 2021-12-05 17:08
tags: [extract, python, lambda, function]
---

# Why use lambda functions?

```python

# Use them as an anonymous function inside another function

def my_func(n):
    return lambda a: a * n
    
my_doubler = my_func(2)

print(my_doubler(11))

```

- [[python-lambda]]
