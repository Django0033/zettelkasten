#extract
#python

# How to create a global variable inside a function in python?
Use the `global` keyword.

```python
def myfunc():
    global x
    x = 'fantastic'

myfunc()

print('Python is ' + x)
```

- [[python-tutorial]]
