# Uncommon HTML Bug: Incorrect div removal

This repository demonstrates a subtle bug in HTML/JavaScript related to removing a div element from the DOM.

The `bug.html` file contains the flawed code.  The `bugSolution.html` file demonstrates the correct approach.

The bug involves incorrectly attempting to remove a div element by setting its `innerHTML` to an empty string. This does not remove the element from the DOM; it only clears its content.  The correct way to remove an element is to use the `removeChild()` method.