Basic JavaScript
----------------------------------------
Function
---------------------------------------------------

Understanding Undefined Value returned from a Function
------------------------------------------------------------
A function can include the return statement but it does not have to. In the case that the function doesn't have a return statement, when you call it, the function processes the inner code but the returned value is undefined.

Assignment with a Returned Value
-------------------------------------------------------------------
If you'll recall from our discussion about Storing Values with the Assignment Operator, everything to the right of the equal sign is resolved before the value is assigned. This means we can take the return value of a function and assign it to a variable.
Assume we have defined a function sum which adds two numbers together.
ourSum = sum(5, 12);
Calling the sum function with the arguments of 5 and 12 produces a return value of 17. This return value is assigned to the ourSum variable

JavaScript Array Methods
-----------------------------------------------------------------------
Array length
Array toString()
Array pop()
Array push()
Array shift()
Array unshift()
Array join()
Array delete()
Array concat()
Array flat()
Array splice()
Array slice()

Comparison with the Strict Equality Operator
------------------------------------------------------------------------------
Strict equality (===) is the counterpart to the equality operator (==). However, unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.
If the values being compared have different types, they are considered unequal, and the strict equality operator will return false.
Examples
3 ===  3  // true
3 === '3' // false
In the second example, 3 is a Number type and '3' is a String type.
