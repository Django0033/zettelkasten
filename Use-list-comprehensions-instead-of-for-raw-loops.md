---
id: Use-list-comprehensions-instead-of-for-raw-loops
aliases: []
tags:
  - extract
  - python
  - list
---

# Use list comprehensions instead of for raw loops

```python
# Bad
squares = []
for i in range(10):
    squares.append(i*i)

print(squares)

# Good
squares = [i*i for i in range(10)]
print(squares)
```

- [[11-Tips-and-Tricks-to-Write-Better-Python-Code.md]]
