---
title: what-is-on-attribute-in-oop
date: 2022-06-06 21:35
---

[Knowledge](Knowledge.md)

# What is an attribute in Object-Oriented Programming

It's a variable that belongs to an object.

```python
class Person:
    def __init__(self, name, age):

        # These are attributes
        self.name = name
        self.age = age

# When we instantiate a new object, we pass values to the object's attributes
p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```

-   [object-oriented-programming](object-oriented-programming.md)
-   [python](python.md)
