---
title: what-is-a-typeerror-in-python
date: 2022-03-07 20:40
---

[Knowledge](Knowledge.md)

# What is a TypeError in Python?

A TypeError is raised when a function passes an argument with the wrong data
type.

```python
def main():
    try:
        text = input('Please enten a number: ')
        integer = round(text) # This will raise a TypeError.
        print(integer)
    except TypeError as type_err:
        print(type_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
