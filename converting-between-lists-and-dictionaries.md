---
title: converting-between-lists-and-dictionaries
date: 2022-02-20 20:00
---

[Knowledge](Knowledge.md)

# Converting between lists and dictionaries

```python
def main():
    # Create a list that contains five student numbers.
    numbers = ["42-039-4736", "61-315-0160",
            "10-450-1203", "75-421-2310", "07-103-5621"]

    # Create a list that contains five student names.
    names = ["Clint Huish", "Michelle Davis",
            "Jorge Soares", "Abdul Ali", "Michelle Davis"]

    # Convert the numbers list and names list into a dictionary.
    student_dict = dict(zip(numbers, names))

    # Print the entire student dictionary.
    print("Dictionary:", student_dict)
    print()

    # Convert the student dictionary into
    # two lists named keys and values.
    keys = list(student_dict.keys())
    values = list(student_dict.values())

    # Print both lists.
    print("Keys:", keys)
    print()
    print("Values:", values)


# Call main to start this program.
if __name__ == "__main__":
    main()
```

-   [python](python.md)
