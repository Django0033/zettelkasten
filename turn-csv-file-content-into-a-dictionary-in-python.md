---
title: turn-csv-file-content-into-a-dictionary-in-python
date: 2022-02-28 21:55
---

[Knowledge](Knowledge.md)

```python
import csv

# If there is a unique item, turn the csv file content into a dictionary
dictionary = {}

with open('<file_name>.csv', 'rt') as csv_file:
    reader = csv.reader(csv_file)
    next(reader)
    for row_list in reader:

        # Use the unique item as the key
        key = row_list[0]
        dictionary[key] = row_list
```

-   [python](python.md)
