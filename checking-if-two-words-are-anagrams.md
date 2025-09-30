---
id: checking-if-two-words-are-anagrams
aliases: []
tags:
  - extracts
  - python
  - string
  - function
date: 2021-12-07 23:31
title: Checking-if-two-words-are-anagrams
---

# Checking if two words are anagrams

```python

def is_anagram(str1, str2):
    return sorted(str1) == sorted(str2)
    
print(is_anagram('geek', 'eegk'))
print(is_anagram('geek', 'peek'))

```

- [[10-essential-python-tips-and-tricks-for-programmers]]
