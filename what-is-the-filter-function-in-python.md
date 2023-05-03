---
title: What is the Filter Function in Python?
date: 2022-03-15 22:49
tags: [knowledge, python, filter, function]
---

# What is the Filter Function in Python?

It's a higher-order function that takes a function that checks certain logic
test and a list as arguments and returns an object that can be turn into a list
that contains only the elements that passed the test.

```python
numbers_list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]


# Function that checks if a number is even
def is_even(number):
    return number % 2 == 0


# filter function recieves the is_even function and numbers_list as arguments
# and returns an object that is turned into a list with the list function and
# the list contains only the even numbers
even_numbers_list = list(filter(is_even, numbers_list))

print(even_numbers_list)
```
