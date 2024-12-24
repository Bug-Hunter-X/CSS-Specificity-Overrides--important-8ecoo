# CSS Specificity Overrides !important

This repository demonstrates an uncommon CSS bug related to specificity and the `!important` declaration.  The bug showcases a situation where a more specific selector overrides a style declaration marked with `!important`.

## Bug Description

The `!important` declaration in CSS usually has the highest precedence. However, specificity rules can override it. This means that a more specific selector, even without the `!important` declaration, will win out over a less specific selector that uses `!important`.

## How to Reproduce

1. Examine the `bug.css` file. 
2. Observe the unexpected color output in a browser due to the conflicting CSS rules.

## Solution

The `solution.css` file provides a corrected approach. By carefully understanding and managing CSS specificity, we can avoid such unexpected outcomes.

## Lessons Learned

This example highlights the importance of understanding CSS specificity and how it interacts with the `!important` declaration.  Overusing `!important` is generally discouraged for maintainability and predictability. It is preferred to rely on correct and well-structured CSS to achieve the desired styling instead.