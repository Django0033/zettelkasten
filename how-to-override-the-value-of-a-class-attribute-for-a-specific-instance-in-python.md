#extract

# How to override the value of a class attribute for a specific instance in Python

```python
class Item:
    pay_rate = 0.8

    def __init__(self, name, price):
        self.name = name
        self.price = price

item1 = Item('Phone', 100)
# This overrides the value of the class attribute pay_rate for this instance
item1.pay_rate = 0.7

print(item1.pay_rate)
```

- [[object-oriented-programming-with-python]]

#python
#object-oriented-programming
