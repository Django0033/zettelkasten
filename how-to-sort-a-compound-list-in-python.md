---
title: how-to-sort-a-compound-list-in-python
date: 2022-03-15 23:28
---

[Knowledge](Knowledge.md)

# How to Sort a Compound List in Python?

```python
countries = [
        # [country_name, land_area, population, gdp_per_capita]
        ["China", 9_600_000_000, 1_340_000_000, 2_300_000_000],
        ["India", 3_287_000_000, 1_240_000_000, 1_200_000_000],
        ["United States", 9_600_000_000, 325_000_000, 2_300_000_000],
        ["Indonesia", 3_287_000_000, 1_240_000_000, 1_200_000_000],
        ["Brazil", 3_287_000_000, 1_240_000_000, 1_200_000_000],
        ["Pakistan", 3_287_000_000, 1_240_000_000, 1_200_000_000]
]

# Create an anonymous function that specifies what column will be used to sort
popul_func = lambda country: country[2]

# sorted funciton takes a list and a function assigned to the key variable as
# arguments. The function is used to sort the list by the specified column.
sorted_list = sorted(countries, key=popul_func)

for country in sorted_list:
    print(country)
```

-   [python](python.md)
