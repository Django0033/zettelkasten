#extract

# How to create a list of the instances of a class in Python

```python
class Item:
    all = []
    def __init__(self, name, price):
        self.name = name
        self.price = price

        # It appends each instance to the all list at its creation
        Item.all.append(self)

    # This magic method formats the representation of each instance
    def __repr__(self):
        return 'Item("{}", {})'.format(self.name, self.price)

item1 = Item('Phone', 100)
item2 = Item('Laptop', 1000)
item3 = Item('Cable', 10)

# Prints the value of the class attribute all
print(Item.all)
```

- [[object-oriented-programming-with-python]]

#python
#object-oriented-programming
