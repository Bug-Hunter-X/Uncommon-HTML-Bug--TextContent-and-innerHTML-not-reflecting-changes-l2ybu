# Uncommon HTML Bug: TextContent and innerHTML Inconsistency

This repository demonstrates an uncommon bug related to how Javascript interacts with the DOM in HTML.  The initial code attempts to change the text content of a div element using both `textContent` and `innerHTML`.  Unexpectedly, neither change is reflected in the rendered HTML, making the text invisible.

The solution demonstrates how to correctly manipulate the DOM to ensure that text changes are visible.