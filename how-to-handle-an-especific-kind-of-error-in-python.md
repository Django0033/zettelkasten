---
title: how-to-handle-an-especific-kind-of-error-in-python
date: 2022-03-07 19:21
---

[Knowledge](Knowledge.md)

# How to Handle an Especific kind of Error in Python?

```python
try:
    # Code that may raise an exception.

except <error_type> as <error_name>:
    # Code that will run if an especific type of exception is raised.
    # Common type of exceptions:
    # - TypeError
    # - ValueError
    # - ZeroDivisionError
    # - IndexError
    # - KeyError
    # - FileNotFoundError
    # - PermissionError
```

-   [python](python.md)
