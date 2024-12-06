# Invalid clip-path polygon coordinate

This repository demonstrates an uncommon CSS bug related to an invalid coordinate in a `clip-path: polygon()` declaration.  The bug results in unexpected or no rendering of the element.  The solution involves correcting the polygon shape to ensure valid coordinates are provided.

## Bug
The `bug.css` file contains the CSS rule causing the issue. This involves an extra coordinate that creates an invalid polygon shape.

## Solution
The `bugSolution.css` file shows the corrected CSS, where the invalid coordinate has been removed, resulting in a valid polygon shape and correct rendering.

## How to reproduce
1. Clone this repository.
2. Open `index.html` (if included) in a web browser.
3. Observe the unexpected behavior caused by the invalid CSS.
4. View the `bugSolution.css` to see how the issue is resolved.