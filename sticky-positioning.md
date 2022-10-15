---
title: sticky-positioning
date: 2022-02-12 18:53
---

#extract
#css

# Sticky Positioning

Setting `position: sticky` on an element will cause the element to scroll with the document just as it would in normal flow, however, once it reaches a certain point in relation to the viewport it sticks and starts to act like `position: fixed`. This is how to create the popular effect of a navigation bar scrolling with the content and then stopping at the top of the viewport to stay onscreen as you scroll the content.

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
  height: 30px;
  background-color: rgba(111,41,97,.3);
  position: sticky;
  top: 0;
  width: 100%;
}
```

- [getting-started-with-css-layout](getting-started-with-css-layout)
