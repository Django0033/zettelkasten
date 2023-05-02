#extract
#python

# How to convert from one numeric data type to another in python?
Use the `int()`, `float()`, and `complex()` methods.

```python
x = 1 # int
y = 2.8 # float
z = 1j # complex

# Convert from int to float:
a = float(x)

# Convert from float to int:
b = int(y)

# Convert from int to complex:
c = complex(x)

print(a) # 1.0
print(b) # 2
print(c) # (1+0j)

print(type(a)) # <class 'float'>
print(type(b)) # <class 'int'>
print(type(c)) # <class 'complex'>
```

- [[python-tutorial]]
