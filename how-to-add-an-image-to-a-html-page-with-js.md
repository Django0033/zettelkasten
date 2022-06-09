---
title: how-to-add-an-image-to-a-html-page-with-js
date: 2022-05-24 22:03
---

[Knowledge](Knowledge.md)

# How to Add an Image to a HTML page with JavaScript

```js
const newImage = document.createElement("img");
newImage.setAttribute("src", "https://placeimg.com/200/200/animals");
newImage.setAttribute("alt", "Image placeholder");
document.body.appendChild(newImage);
```

- [javascript](javascript.md)
