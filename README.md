# Uncommon CSS `calc()` Function Errors

This repository demonstrates some less common errors that can arise when using the `calc()` function in CSS.  These errors often involve unexpected behavior related to unit inconsistencies and exceeding the available space within a parent element. 

## Bug Description
The `calc()` function, while powerful, requires careful attention to detail. Incorrect usage can lead to unexpected results in terms of element sizing and layout. This is especially true when combining percentages, pixels, ems, or other units within the same calculation.

## How to Reproduce
Examine the `bug.css` file for examples of problematic `calc()` function usages. You can create a simple HTML file with some divs and apply these CSS rules to observe the errors.

## Solution
The `bugSolution.css` file provides corrected versions of the CSS code. It emphasizes using consistent units and ensuring that the calculated values don't exceed the available space within the parent container. Always double-check your unit usage and context when using `calc()`.