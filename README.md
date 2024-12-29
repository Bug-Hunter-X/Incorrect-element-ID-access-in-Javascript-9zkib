# Uncommon HTML Bug: Incorrect Element ID Access
This repository demonstrates a common yet often overlooked error in HTML/JavaScript interaction: incorrect access to element IDs.
The `bug.html` file contains the erroneous code, while `bugSolution.html` provides the corrected version.  The issue stems from failing to properly quote the ID when using `document.getElementById()`.  This leads to a runtime error.
The solution involves properly quoting the ID string within the `getElementById` method call.
