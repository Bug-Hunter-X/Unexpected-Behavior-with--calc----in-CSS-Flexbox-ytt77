# Unexpected Behavior with `calc()` in CSS Flexbox

This repository demonstrates a common yet subtle issue with the CSS `calc()` function, particularly when used within flexbox layouts.  The problem arises when `calc()` is used to define a dimension that depends on the parent container's size, but the parent's size isn't explicitly defined.

The `bug.css` file showcases the problematic code. The `solution.css` file provides a corrected version.

## Reproduction Steps

1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file to see the visual effect).
3. Observe the unexpected behavior in the original CSS.
4. Compare with the corrected CSS for the intended layout.