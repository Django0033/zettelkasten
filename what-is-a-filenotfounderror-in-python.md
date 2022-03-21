---
title: what-is-a-filenotfounderror-in-python
date: 2022-03-07 21:36
---

[Knowledge](Knowledge.md)

# What is a FileNotFoundError in Python?

A FileNotFoudError is raised when a program tries to open a file for reading and
that file doesn't exist.

```python
dey main():
    try:
        with open('file.txt', 'rt') as f:   # This will raise a FileNotFoundError
                                            # if the file doesn't exist.
            for line in f:
                print(line)

    except FileNotFoundError as not_found_err:
        print(not_found_err)

if __name__ == '__main__':
    main()
```

-   [python](python.md)
