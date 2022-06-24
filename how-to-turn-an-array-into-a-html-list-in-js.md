---
title: how-to-turn-an-array-into-a-html-list-in-js
date: 2022-05-25 23:39
---

[Knowledge](Knowledge.md)

# How to turn an array into a HTML list in JavaScript

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Arrays</title>
        <script src="arrays.js" defer></script>
    </head>
    <body>
        <ul id="myList"></ul>
    </body>
</html>
```

```js
const steps = ["one", "two", "three"];

// Creat a new array with `li` elements
const stepsHtml = steps.map(function (step) {
    return `<li>${step}</li>`;
});

// Join the elements with carret returns and put it inside the element with the
// `myList` id
document.getElementById("myList").innerHTML = stepsHtml.join("\n");
```

-   [javascript](javascript.md)
