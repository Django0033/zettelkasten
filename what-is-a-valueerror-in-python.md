---
title: what-is-a-valueerror-in-python
date: 2022-03-07 20:47
---

[Knowledge](Knowledge.md)

# What is a ValueError in Python?

A ValueError is raised when a function is called with the correct data type but with an invalid value.

```python
def main():
    try:
        number = float(input('Please enter a number: ')) # This will raise a ValueError exception if the user passes a string.
        print(number)

    except ValueError as val_err:
        print(val_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
