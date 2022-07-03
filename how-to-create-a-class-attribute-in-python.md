#extract

# How to create a class attribute in Python

```python
class Item:
    pay_rate = 0.8 # This is a class attribute

    def __init__(self, name, price):
        self.name = name
        self.price = price

# Don't need to pass an argument for the class attribute
item1 = Item('Phone', 100)
```

- [[object-oriented-programming-with-python]]

#python
#object-oriented-programming
