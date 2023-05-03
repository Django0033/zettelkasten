---
title: Compound list
date: 2022-02-11 14:11
tags: [ extract, python ]
---

# Compound list

```python
# Create a compound list that stores smaller lists.
apple_tree_data = [
    # [year_planted, height, girth, fruit_amount],
    [2012, 2.7, 3.6, 70.5],
    [2012, 2.4, 3.7, 81.3],
    [2015, 2.3, 3.6, 62.7],
    [2016, 2.1, 2.7, 42.1],
]

# These are the indexes of each
# element in the inner lists.
year_planted_index = 0
height_index = 1
girth_index = 2
fruit_amount_index = 3

# Retrieve one inner list from the compound list.
one_tree = apple_tree_data[2]

# Retrieve one value from the inner list.
one_tree_height = one_tree[height_index]

# Print the tree's height.
print("height: {}".format(one_tree_height))
```

- [[list-and-repetition]]

