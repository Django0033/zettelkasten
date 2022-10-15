---
title: fixed-positioning
date: 2022-02-12 18:33
---

#extract
#css

# Fixed Positioning

Somthing with `position: fixed` will be positioned in most cases relative to the viewport, and removed from document flow so that no space is reserved for it. This can be helpful to enable a fixed navigation panel which stays on screen while the content scrolls.

```html
<div class="container">

  <p>Pea horseradish azuki bean lettuce avocado asparagus okra. Kohlrabi radish okra azuki bean corn fava bean mustard tigernut jícama green bean celtuce. </p>

  <div class="item"></div>
  <p>Grape silver beet  collard greens avocado quandong fennel gumbo black-eyed pea watercress potato tigernut corn groundnut. Chickweed okra pea winter purslane coriander yarrow sweet pepper radish garlic brussels sprout groundnut summer purslane earthnut pea tomato spring onion azuki bean gourd. Gumbo kakadu plum komatsuna black-eyed pea green bean zucchini gourd winter purslane silver beet rock melon radish asparagus spinach.</p>

   <p>Grape silver beet  collard greens avocado quandong fennel gumbo black-eyed pea watercress potato tigernut corn groundnut. Chickweed okra pea winter purslane coriander yarrow sweet pepper radish garlic brussels sprout groundnut summer purslane earthnut pea tomato spring onion azuki bean gourd. Gumbo kakadu plum komatsuna black-eyed pea green bean zucchini gourd winter purslane silver beet rock melon radish asparagus spinach.</p>

   <p>Grape silver beet  collard greens avocado quandong fennel gumbo black-eyed pea watercress potato tigernut corn groundnut. Chickweed okra pea winter purslane coriander yarrow sweet pepper radish garlic brussels sprout groundnut summer purslane earthnut pea tomato spring onion azuki bean gourd. Gumbo kakadu plum komatsuna black-eyed pea green bean zucchini gourd winter purslane silver beet rock melon radish asparagus spinach.</p>
</div>
```

```css
body {
  padding: 20px;
  font: 1em Helvetica Neue, Helvetica, Arial, sans-serif;
}

p {
  margin: 0 0 1em 0;
}

.container {
  width: 500px;
  border: 5px solid rgb(111,41,97);
  border-radius: .5em;
  padding: 10px;
  position: relative;
}

.item {
  width: 100px;
  height: 100px;
  background-color: rgba(111,41,97,.3);
  position: fixed;
  top: 20px;
  left: 20px;
}
```

- [getting-started-with-css-layout](getting-started-with-css-layout)
