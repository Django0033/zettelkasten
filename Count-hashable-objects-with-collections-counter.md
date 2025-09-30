---
id: Count-hashable-objects-with-collections-counter
aliases: []
tags:
  - extract
  - python
  - collections
  - counter
---

# Count Hashable Objects with collections counter

```python
from collections import Counter

my_list = [10,10,10,5,5,2,9,9,9,9,9,9,9]
counter = Counter(my_list) # Creates a dict with unique items from the list and the number of times the item appears in the list.

print(counter)
print(counter[10]) # Prints the value of the key "10" in the dict.

most_common = counter.most_common(1) # Returns the most common item. The argument especifies the number fo items.
print(most_common)
```

- [[11-Tips-and-Tricks-to-Write-Better-Python-Code.md]]
