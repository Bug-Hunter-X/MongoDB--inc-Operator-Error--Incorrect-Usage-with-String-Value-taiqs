# MongoDB $inc Operator Error: Incorrect Usage with String Value

This example demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numeric field by a specified value.  However, if you provide a string value instead of a number, you'll encounter an error.

## Bug:
The provided code attempts to increment the 'field' value by '1' (a string).  This results in an error because `$inc` expects a number.

## Solution:
The solution shows the correct usage of the `$inc` operator, providing the numerical value (1) instead of the string ('1').