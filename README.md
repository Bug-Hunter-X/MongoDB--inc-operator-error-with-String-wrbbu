# MongoDB $inc Operator Error with String

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number will lead to unexpected behavior.

The `bug.js` file shows the incorrect usage, resulting in an unintended update. The `bugSolution.js` file presents the corrected code.