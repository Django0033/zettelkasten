# [[Extracts]]

```python
import sys

my_list = [i for i in range(10000)]
print(sum(my_list))
print(sys.getsizeof(my_list), 'bytes')

my_gen = (i for i in range(10000))
print(sum(my_gen))
print(sys.getsizeof(my_gen), 'bytes')
```

Reduces memory usage.

- [[11-Tips-and-Tricks-to-Write-Better-Python-Code]]
- [[python]]
