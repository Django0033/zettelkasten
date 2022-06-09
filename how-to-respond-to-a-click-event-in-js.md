---
title: how-to-respond-to-a-click-event-in-js
date: 2022-05-25 22:11
---

[Knowledge](Knowledge.md)

# How to respond to a click event in JavaScript

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Test</title>
    </head>

    <body>
        <h2>addEventListener</h2>
        <input id="inputBox" type="text" />
        <button id="submitButton">Submit</button>
        <p id="output"></p>
    </body>

    <script>
        // Assign the element with the id `submitButton` to the variable
        // buttonElement
        const buttonElement = document.getElementById("submitButton");

        function copyInput() {
            const inputElement = document.getElementById("inputBox");
            const outputElement = document.getElementById("output");
            outputElement.innerHTML = inputElement.value;
        }

        // Use the addEventListener method to add event listeners to the
        // buttonElement waiting for click
        buttonElement.addEventListener("click", copyInput);
    </script>
</html>
```

-   [javascript](javascript.md)
-   [javascript](javascript.md)
