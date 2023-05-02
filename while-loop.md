---
title: While loop
date: 2022-02-11 15:38
tags: [extract, python, while, loop]
---

# While loop

```python
def main():
    list1 = ["red", "orange", "yellow", "green", "blue"]
    list2 = ["red", "orange", "green", "green", "blue"]
    index = compare_lists(list1, list2)
    if index == -1:
        print("The lists are identical")
    else:
        print("The lists are different")
        print("The first different index is", index)


def compare_lists(list1, list2):
    """Compare the contents of two lists. If the contents of the two lists are
    not equal, return the index of the first difference. If the contents of the
    two lists are equal, return -1.

    Parameters:
        list1 (list): The first list to compare.
        list2 (list): The second list to compare.

    Returns:
        int: The index of the first difference between the two lists. If the
        two lists are identical, return -1.
    """
    # Get the length of the shorter list.
    length1 = len(list1)
    length2 = len(list2)
    limit = min(length1, length2)

    # Begin at the first index (0) and repeat until the computer finds two
    # elements that are not equal or until the computer reaches the end of the
    # shortest list, whichever comes first.
    i = 0
    while i < limit:  # Loops until this condition is false.
        # Retrieve one element from each list.
        element1 = list1[i]
        element2 = list2[i]

        # if the two elements are not equal, quit the while loop
        if element1 != element2:
            break

        # Add one to the index variable.
        i += 1

    # If the length of both lists ore equal and the computer verified that all
    # elements are equal, set i to -1 to indicate that the contents of the two
    # lists are equal.
    if length1 == length2 == i:
        i = -1

    return i


# Call main to start this program.
if __name__ == "__main__":
    main()
```

- [[list-and-repetition]]
