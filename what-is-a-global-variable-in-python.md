#extract
#python

# What is a global variable in python?
It's a variable that is created outside of a function and can be used inside or
outside functions.

If you create a variable with the same name inside a function, this variable
will be local. The global variable will remain with the same value.

```python
x = 'awesome'

def myfunc():
    print('Python is ' + x)

myfunc()
```

- [[python-tutorial]]
