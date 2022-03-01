---
title: multiple-acces-to-the-csv-file-content-in-python
date: 2022-02-28 21:37
---

[Knowledge](Knowledge.md)

# Multiple Access to the CSV File Content in Python

```python
import csv

# If a program needs to read the content of a CSV file multiple times, store the
# conetent in a compound list.
compound list = []

with open('<file_name>.csv, 'rt') as csv_file:
    reader = csv.reader(csv_file)
    next(reader)

    for row in reader:
        compound_list.append(row)

print compound_list
```

-   [python](python.md)
