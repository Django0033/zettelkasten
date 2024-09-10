---
title: How to insert numbers into strings in python
date: 2024-01-06
tags: [extract,python,integer,float,string]
---

# How to insert numbers into strings in python

```python
age = 36
txt = 'My name is John, and I am {}'

# Prints 'My name is John, and I am 36'
print(txt.format(age))

quantity = 3
itemno = 567
price = 49.95
myorder = 'I want {} pieces of item {} for {} dollars.'

# `format()` can take unlimited number of arguments.
print(myorder.format(quantity,itemno,price))

# Use index numbers to be sure the arguments are placed in the correct
placeholders.
myorder = 'I want to pay {2} dollars for {0} pieces of item {1}.'

print(myorder.format(quantity,itemno,price))
```

- [[python-tutorial]]
