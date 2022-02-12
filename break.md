---
title: break
date: 2022-02-11 15:02
---
# [Extracts](Extracts)

```python
def main():

    sum = 0

    # Get ten or fewer numbers from the user and
    # add them together.
    for i in range(10):
        number = float(input("Enter a number: "))
        if number == 0:
            break  # break out of the loop
        sum += number

    # Print the sum of the numbers for the user to see.
    print("sum: {}".format(sum))


# Call main to start this program.
if __name__ == "__main__":
    main()
```

[python](python)
[list-and-repetition](list-and-repetition)
