---
title: Why-use-lambda-functions
date: 2021-12-05 17:08
---
# [Extracts](Extracts)

```python

# Use them as an anonymous function inside another function

def my_func(n):
    return lambda a: a * n
    
my_doubler = my_func(2)

print(my_doubler(11))

```

- [Python-lambda](python-lambda)
- [python](python)
