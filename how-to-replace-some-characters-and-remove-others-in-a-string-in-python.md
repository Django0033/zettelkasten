---
title: how-to-replace-some-characters-and-remove-others-in-a-string-in-python
date: 2022-04-14 13:00
---

[Extracts](Extracts.md)

# How to Replace Some Characters and Remove Others in a String in Python?

```python
text = 'Good night Sam'
x = 'mSa'
y = 'eJo'
z = 'odnght'

# Replaces all instances of x with y and removes all instances of z
mytable = text.maketrans(x, y, z)
print(txt.translate(mytable))
```

-   [python-string-maketrans-method](python-string-maketrans-method.md)
-   [python](python.md)
