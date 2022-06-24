---
title: what-is-an-indexerror-in-python
date: 2022-03-07 21:25
---

[Knowledge](Knowledge.md)

# What is an IndexError in Python?

An IndexError is raised when a program tries to use an index that doesn't exist.

```python
def main():
    try:
        a = [1, 2, 3]
        print(a[3]) # This will raise an IndexError

    except IndexError as index_err:
        print(index_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
