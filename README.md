# Unexpected Behavior of `calc()` in Flexbox

This repository demonstrates an uncommon issue related to the `calc()` function in CSS when used within flexbox layouts. The problem arises from inconsistencies in how different browsers handle calculations involving percentages and lengths in this context.

## Problem Description

When using `calc()` to define widths (or heights) of flex items, the expected behavior isn't always consistent across different browsers. The `calc()` function might not produce the intended result due to variations in how the flexbox algorithm handles calculations and space distribution.

## Reproduction

The `bug.css` file contains the CSS code that reproduces the problem. You'll find that the space occupied by flex items doesn't perfectly align with the expected layout.  

## Solution

The `bugSolution.css` file presents a potential solution. Consider alternative approaches for achieving the intended layout. In some cases, a more explicit approach, avoiding `calc()` within flexbox and employing techniques such as margins, may provide more reliable results.