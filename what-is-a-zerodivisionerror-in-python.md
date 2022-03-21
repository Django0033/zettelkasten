---
title: what-is-a-zerodivisionerror-in-python
date: 2022-03-07 21:18
---

[Knowledge](Knowledge.md)

# What is a ZeroDivisionError in Python?

A ZeroDivisionError is raised when a program trys to divide a number by zero.

```python
def main():
    try:
        print(5/0) # Ths will raise a ZeroDivisionError

    except ZeroDivisionError as zero_div_err:
        print(zero_div_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
