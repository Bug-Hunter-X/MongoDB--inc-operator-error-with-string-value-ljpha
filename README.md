# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical field by a specified value.  However, if the value provided is a string instead of a number, MongoDB will throw an error. 

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the correct implementation.