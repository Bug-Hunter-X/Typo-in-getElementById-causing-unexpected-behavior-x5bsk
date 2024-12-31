# Uncommon HTML Bug: Misspelled getElementById

This repository demonstrates a subtle yet common error in HTML/JavaScript: misspelling `getElementById`.  The code attempts to access a div element but uses an incorrect function name, leading to `null` being returned and the update failing silently.

## Bug

The `bug.html` file contains the erroneous code.  The script incorrectly uses `getElementByIdx` instead of `getElementById`. This typo prevents the script from correctly accessing the div, and the innerHTML is not updated.

## Solution

The `bugSolution.html` file demonstrates the correct way to access the div element using the correctly spelled `getElementById` function.

## Learning Points

- Pay close attention to detail when writing JavaScript, especially when using DOM manipulation functions.
- Use your browser's developer console to debug issues; it often reveals errors that are not immediately apparent in the code itself.   