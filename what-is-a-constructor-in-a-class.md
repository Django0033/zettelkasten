---
title: what-is-a-constructor-in-a-class
date: 2022-06-06 21:25
---

[Knowledge](Knowledge.md)

# What is a constructor in a class?

It's a special method that initializes attributes when we instantiate a new
object

```python
class Person:

    # This is the constructor
    def __init__(self, name, age):
        self.name = name
        self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```

-   [object-oriented-programming](object-oriented-programming.md)
-   [python](python.md)
