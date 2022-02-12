---
title: list-reference
date: 2022-02-11 16:21
---
# [Extracts](Extracts)

```python
def main():

    lx = [7, -2] # Creates a list and stores a reference to that list in the variable lx
    ly = lx # Copies the reference in the variable lx into the variable ly. Does not create a new list.

    print("Before changing lx: lx {} ly {}".format(lx, ly))

    lx.append(5)

    print("After changing lx: lx {} ly {}".format(lx, ly))


# Call main to start this program.
if __name__ == "__main__":
    main()
```

[python](python)
[list-and-repetition](list-and-repetition)
