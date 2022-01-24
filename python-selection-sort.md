---
title: python-selection-sort
date: 2022-01-01 11:19
---

# [Extracts](Extracts)

```python
unsorted_list = [64, 25, 12, 22, 11]

for i in range(len(unsorted_list)):
    print('''
    for i in range(len(unsorted_list)):
    i = {}
    len(unsorted_list) = {}
    '''.format(i, len(unsorted_list)))
    
    min_idx = i
    print('''
    min_idx = i
    min_idx = {}
    '''.format(min_idx))

    for j in range(i+1, len(unsorted_list)):
        print('''
        for j in range(i+1, len(unsorted_list)):
        j = {}
        i + 1 = {}
        len(unsorted_list) = {}
        '''.format(j, i + 1, len(unsorted_list)))

        if unsorted_list[j] < unsorted_list[min_idx]:
            print('''
            if unsorted_list[j] < unsorted_list[min_idx]:
            unsorted_list[j] = {}
            unsorted_list[min_idx] = {}
                    '''.format(unsorted_list[j], unsorted_list[min_idx]))
            min_idx = j
            print('''
            min_idx = j
            min_idx = {}
            '''.format(min_idx))

    unsorted_list[i], unsorted_list[min_idx] = unsorted_list[min_idx], unsorted_list[i]
    print('''
    unsorted_list[i], unsorted_list[min_idx] = unsorted_list[min_idx], unsorted_list[i]
    unsorted_list[i] = {}
    unsorted_list[min_idx] = {}
    '''.format(unsorted_list[i], unsorted_list[min_idx]))

print('''
Sorted list: {}
        ''' .format(unsorted_list))
```

[python](python)
[selection-sort](selection-sort)
