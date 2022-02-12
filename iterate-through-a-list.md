---
title: iterate-through-a-list
date: 2022-02-11 14:53
---
# [Extracts](Extracts)

```python
def main():

    # Create a list of color names
    colors = ["red", "orange", "yellow", "green", "blue"]

    # Use a for loop to print each element in the list
    for color in colors:
        print(color)
    print()

    # Use a different for loop to
    # print each element in the list
    for index in range(len(colors)):
        print(colors[index])

    # Of course, the code in the body of a loop can do
    # much more with each element than simply print it.


# Call main to start this program.
if __name__ == "__main__":
    main()
```

[python](python)
[list-and-repetition](list-and-repetition)
