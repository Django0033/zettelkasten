---
title: reading-csv-files-in-python
date: 2022-02-28 20:50
---

[Knowledge](Knowledge.md)

# Reading CSV Files in Python

```python
import csv

with open('<file_name>.csv', 'rt') as csv_file:

    # Creates an object object that stores each row of the CSV file as a list.
    reader = csv.reader(csv_file)

    for row_list in reader:
        print(row_list)
```

-   [python](python.md)
