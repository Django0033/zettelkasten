# [[Knowledge]]

```python
shopping_cart = [
    ['Chips', 2.99],
    ['Bread', 2.50],
    ['Milk', 3.19],
    ['Ice Cream', 6.99],
    ['Cheese', 5.99],
    ['Candy bar', 0.99]
]
max_price = -1

for item in shopping_cart:
    price = item[1] # The price is the second part of the item

    if price > max_price:
        # This is the new max
        max_price = price

print(f'The maximum price is: {max_price}')
```

- [[python]]
