# Redundant CSS Properties in HTML

This example demonstrates an uncommon error in HTML related to the redundant use of CSS properties `display: none;` and `visibility: hidden;` to hide an HTML element.  While both properties can hide an element, using them together is unnecessary and can potentially cause unexpected layout issues.

## Bug Description

The `bug.html` file shows an HTML element with its style set to both `display: none;` and `visibility: hidden;`.  The `display: none;` property is sufficient to completely hide the element; using `visibility: hidden;` in addition is redundant.

## Solution

The `bugSolution.html` file corrects the issue by removing the redundant `visibility: hidden;` property.  This ensures that the element is properly hidden without any potential conflicts or unexpected behavior.