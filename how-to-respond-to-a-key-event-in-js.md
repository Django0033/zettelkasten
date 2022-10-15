---
title: how-to-respond-to-a-key-event-in-js
date: 2022-05-25 22:25
---

#knowledge
#javascript

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Test</title>
    </head>

    <body>
        <p id="log"></p>
    </body>

    <script>
        // Assign the element with the `log` id to the variable `log`
        const log = document.querySelector("#log");

        // Add a listener to the document object waiting for a key to be
        // pressed
        document.addEventListener("keydown", logKey);

        function logKey(e) {
            console.log(e);
        }
    </script>
</html>
```
