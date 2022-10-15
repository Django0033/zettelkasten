---
title: flex-layout
date: 2022-02-13 10:00
---

#extract
#css

# Flex Layout

It is used when you want to layout your content in a row or a column.

```html
<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
</div>
```

```css
body {
    padding: 20px;
    font: 1em Helvetica Neue, Helvetica, Arial, sans-serif;
}

* {
    box-sizing: border-box;
}

.container {
    width: 500px;
    border: 5px solid rgb(111,41,97);
    border-radius: .5em;
    padding: 10px;
    display: flex;
}

.item {
    width: 100px;
    height: 100px;
    padding: 10px;
    background-color: rgba(111,41,97,.3);
    border: 2px solid rgba(111,41,97,.5)
}
```

- [getting-started-with-css-layout](getting-started-with-css-layout)
