# CSS Specificity Issue with Nested :hover Pseudo-class

This repository demonstrates a common CSS issue related to specificity when using the `:hover` pseudo-class on nested elements.  The problem arises because the parent element's `:hover` style overrides the child's `:hover` style due to higher specificity.

The `bug.css` file contains the problematic CSS code, and `bugSolution.css` demonstrates how to solve the issue using the `!important` flag or by adjusting the CSS selector specificity.