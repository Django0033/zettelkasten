#extract
#python

# How to change the value of a global variable from inside a function in python?
Refer to the global variable you want to change using the `global` keyword.

```python
x = 'awesome'

def myfunc():
    global x
    x = 'fantastic'

myfunc()

print('Python is ' + x)

# Output-> 'Python is fantastic'
```

- [[python-tutorial]]
