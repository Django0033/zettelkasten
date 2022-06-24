---
title: what-is-a-keyerror-in-python
date: 2022-03-07 21:30
---

[Knowledge](Knowledge.md)

# What is a KeyError in Python?

A KeyError is raised when a program tries tu use a key that doesn't exist.

```python
def main():
    try:
        dict = {'a': 1, 'b': 2}
        print(dict['c']) # This will raise a KeyError

    except KeyError as key_err:
        print(key_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
