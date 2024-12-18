# CSS calc() function inconsistency
This repository demonstrates a bug related to the inconsistency in how different browsers handle the CSS `calc()` function when combining percentages, pixels, and ems within a single calculation.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides a potential workaround or clarification on how to use calc() to avoid this issue. The problem becomes evident when testing across various browsers (e.g., Chrome, Firefox, Safari).

## How to reproduce
1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file to test it, e.g., with a div element). 
3. Inspect the element's width in different browsers. You should see different results depending on the browser and the screen size.

## Workaround and explanation