This repository demonstrates two uncommon HTML errors:

1. **Accessing Non-Existent Attributes:** Attempting to retrieve the value of a non-existent attribute using `getAttribute()` will return `null`, but can sometimes lead to unexpected behavior in your JavaScript code if not handled correctly.
2. **Using Deprecated Tags:** Certain HTML tags, such as `<blink>`, are deprecated and not supported by modern browsers. Using these tags can result in inconsistent rendering and unexpected behavior across browsers.

The `bug.html` file shows the errors. The `bugSolution.html` file demonstrates best practices to handle accessing non-existent attributes and avoiding deprecated tags.