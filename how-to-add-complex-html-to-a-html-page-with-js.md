---
title: how-to-add-complex-html-to-a-html-page-with-js
date: 2022-05-24 22:05
---

[Knowledge](Knowledge.md)

# How to Add Complex HTML to a HTML page with JavaScript

```js
const newDiv = document.createElement("div");

newDiv.innerHTML = "<ul><li>One</li><li>Two</li><li>Three</li></ul>";

document.body.appendChild(newDiv);
```

-   [javascript](javascript.md)
