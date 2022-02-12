---
title: clearing-floats
date: 2022-02-12 11:22
---

[Extracts](Extracts)

# Clearing Floats

It prevents the following elements to wrap around the floated element. Add the declaration on the element that you want to begin displaying after the float.

```css
.clear {
    clear: both;
}
```

It won't help if the floated item is inside a box with some text alongside. Solution: add CSS generated content, and set that to clear both.

```html
<div class="container">
    <div class="item"></div>
    <p>Pea horseradish azuki bean lettuce avocado asparagus okra.</p>

</div>
```

```css
p {
    margin: 0 0 1em 0;
}

.container {
    width: 500px;
    border: 5px solid rgb(111, 41, 97);
    border-radius: .5em;
    padding: 10px;
}

.item {
    width: 100px;
    height: 100px;
    float: left;
    margin: 0 20px 20px 0;
    background-color: rgba(111,41,97,.3);
}

.container::after {
    content: "";
    display: table;
    clear: both;
}
```

- [getting-started-with-css-layout](getting-started-with-css-layout)
- [css](css)
