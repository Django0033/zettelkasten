#extract

# How to access a class attribute in Python

```python
class Item:
    pay_rate = 0.8 # Class attribute

    def __init__(self, name, price):
        self.name = name
        self.price = price

# This access the pay_rate class attribute and prints it
print(Item.pay_rate)

item1 = Item('Phone', 100)
# This will check at the instance level, if it doesn't find the attribute, it
# checks in the class level
print(item1.pay_rate)
```

- [[object-oriented-programming-with-python]]

#python
#object-oriented-programming
