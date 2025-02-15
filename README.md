# Silent Script Failure in HTML

This repository demonstrates an uncommon HTML error where a script tag is placed within an element that doesn't support scripting, causing the script to fail silently.  This is a tricky error because it doesn't throw a typical JavaScript error. The browser parses the script, but it doesn't execute.

## Problem

The `bug.html` file shows the problematic code.  A script tag is incorrectly placed within a `<p>` element. While the browser parses the HTML without generating a visible error, the alert within the script never runs.

## Solution

The `bugSolution.html` file demonstrates the correct way to include the script tag in the `<head>` or `<body>` of the HTML document, ensuring it executes as expected.