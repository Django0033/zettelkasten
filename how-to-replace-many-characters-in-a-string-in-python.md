---
title: how-to-replace-many-characters-in-a-string-in-python
date: 2022-04-14 12:32
---

[Extracts](Extracts.md)

# How to Replace Many Characters in a String in Python?

```python
text = 'Hi Sam!'
x = 'mSa'
y = 'eJo'

# Creates a table where 'm' = 'e', 'S' = 'J', and 'a' = 'o'
mytable = str.maketrans(x, y)

# Replaces charactes according to the table
new_text = text.translate(mytable)

print(new_text)
```

-   [python string maketrans method](python-string-maketrans-method.md)
-   [python](python.md)
