---
id: how-to-find-the-most-frequent-item-in-a-list-in-python
aliases: []
tags:
  - extracts
  - python
  - list
---

# How to find the most frequent item in a list in python

```python

test = [1, 2, 3, 4, 2, 2, 3, 1, 4, 4, 4]

print(max(set(test), key = test.count))

```

- [[10-essential-python-tips-and-tricks-for-programmers]]
