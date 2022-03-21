---
title: what-is-a-permissionerror-in-python
date: 2022-03-07 21:44
---

[Knowledge](Knowledge.md)

# What is a PermissionError in Python?

A PermissionError is raised when a program tries to acccess a file that is protected.

```python
def main():
    try:
        with open('sys32.txt', 'rt') as f:  # This will raise a PermissionError
                                            # if tha file is protected
            print(f.read())

    except PermissionError as perm_err:
        print(perm_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
