# CSS calc() Unexpected Behavior

This repository demonstrates an unexpected behavior with the CSS `calc()` function when using percentages and viewport units together.  The issue arises from the way `calc()` handles these units in dynamic viewport situations.

## Bug Report

The code in `bug.css` demonstrates the problem.  Observe how the width of the element doesn't always calculate correctly as the viewport width changes.

## Solution

The `bugSolution.css` file offers a possible solution or workaround. This solution might involve using alternative approaches, such as media queries or JavaScript, to manage layout responsiveness more effectively.