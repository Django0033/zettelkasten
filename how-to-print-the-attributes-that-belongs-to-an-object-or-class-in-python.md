[Extracts](Extracts.md)

# How to print the attributes that belongs to an object or class in Python

```python
def Item:
    pay rate = 0.8
    
    def __init__(self, name, price, quantity)
    self.name = name
    self.price = price
    self. quantity = quantity

item1 = Item('Phone', 100, 5)

# Print all the attributes that belongs to the class
print(Item.__dict__)

# Print all the attributes that belongs to the object
print(item1.__dict__)
```

- [[object-oriented-programming-with-python]]
- [[python]]
- [[object-oriented-programming]]
