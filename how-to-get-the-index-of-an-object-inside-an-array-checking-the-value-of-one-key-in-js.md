---
title: how-to-get-the-index-of-an-object-inside-an-array-checking-the-value-of-one-key-in-js
date: 2022-05-30 22:19
---

[Knowledge](Knowledge.md)

# How to get the index of an object inside an array checking the value of one key in JavaScript

```js
let arrayOfObjects = [{A: 1,  2}, {A: 3, B: 4}, {A: 5, B: 6}]
let userInput = 3

let objectIndex = arrayOfObjects.indexOf(
(object) => object.A === userInput
)
```

-   [javascript](javascript.md)
