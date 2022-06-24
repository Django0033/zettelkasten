---
title: how-to-add-all-the-numbers-in-an-array-in-js
date: 2022-05-26 21:04
---

[Knowledge](Knowledge.md)

# How to add all the numbers in an array in JavaScript

```js
let numbers = [1, 2, 3];

// Create a function that adds numbers to a total
function sumRunningTotal(total, num) {
    return total + num;
}

// Use reduce method to apply the function to each number in the array
let runningTotal = numbers.reduce(sumRunningTotal);
```

-   [javascript](javascript.md)
