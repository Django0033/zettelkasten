---
title: handling-csv-heading-in-python
date: 2022-02-28 21:02
---

[Knowledge](Knowledge.md)

```python
import csv

with open('<file_name>.csv', 'rt') as csv_file:
    reader = csv.reader(csv_file)

    # Skip the first row of the CSV file (header)
    next(reader)

    for row_list in reader:
        print(row_list)
```

-   [python](python.md)
