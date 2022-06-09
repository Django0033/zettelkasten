---
title: what-is-an-instance-of-a-class-in-oop
date: 2022-06-07 00:20
---

[Knowledge](Knowledge.md)

# What is an instance of a class in Object-Oriented Programming

It's the realization of the attributes and methods of a class.

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def hello(self):
        print("Hellow my name is {}".format(self.name))

# This is an instance of the class Person
p1 = Person("John", 36)
```

-   [object-oriented-programming](object-oriented-programming.md)
-   [python](python.md)
