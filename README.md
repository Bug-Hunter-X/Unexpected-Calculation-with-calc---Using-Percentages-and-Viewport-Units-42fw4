# Unexpected Calculation with calc() Using Percentages and Viewport Units

This repository demonstrates a bug where the `calc()` function in CSS produces unexpected results when combining percentages and viewport units (like `vw` or `vh`).  The expected calculation doesn't match the rendered output.

## Bug Description
The CSS `calc()` function is not correctly calculating expressions involving percentages and viewport units. This leads to unexpected layout issues.

## Solution
The solution involves refactoring the `calc()` expression to avoid the problematic combination of percentages and viewport units.  Alternative approaches may include using JavaScript for dynamic calculations or adjusting the CSS structure to remove the need for the problematic `calc()` expression.