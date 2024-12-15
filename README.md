# Unexpected Behavior and Miscalculations in CSS `calc()`

This repository demonstrates some uncommon issues that can arise when using the CSS `calc()` function, specifically related to nested percentages, viewport units, and operator precedence. The `bug.css` file showcases the problematic code, while `bugSolution.css` provides solutions and best practices to avoid these pitfalls.  Understanding how `calc()` interacts with percentages and viewport units within different contexts is crucial for predictable results. Incorrect operator precedence can also lead to unexpected calculations, highlighting the importance of proper parentheses usage.

## How to reproduce

1. Open `bug.html` in a web browser.
2. Observe the unexpected width of the elements due to nested percentage calculation.
3. Compare this with the corrected layout in `bugSolution.html`