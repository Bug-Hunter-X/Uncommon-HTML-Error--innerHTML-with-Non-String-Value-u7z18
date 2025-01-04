# Uncommon HTML Error: innerHTML with Non-String Value

This repository demonstrates an uncommon error in HTML related to the `innerHTML` property.  Specifically, it highlights the issue of attempting to set `innerHTML` to a non-string value.

## The Bug
The `bug.html` file contains a simple HTML page with a div element. A JavaScript snippet attempts to set the `innerHTML` of this div to the number 123. This is incorrect; `innerHTML` expects a string.

## The Solution
The `bugSolution.html` file provides the corrected version.  It explicitly converts the numerical value to a string before assigning it to `innerHTML`.