---
title: what-is-a-method-in-oop
date: 2022-06-06 21:14
---

[Knowledge](Knowledge.md)

# What is a method in Object-Oriented Programming

It's a function that belongs to an object.

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    # This is a method
    def myFunc(self):
        print("Hello my name is {}".format(self.name))

p1 = Person("John", 36)
p1.myFunc()
```

-   [object-oriented-programming](object-oriented-programming.md)
