# Null Object Reference Error in ActionScript 3

This repository demonstrates a common error in ActionScript 3: the null object reference error.  The error occurs when attempting to access a property or method of an object that is null or undefined.  The example shows how this error can occur and provides a solution using null checks.

## Bug

The `bug.as` file contains code that attempts to access the `someProperty` of an object (`param1`). If `param1` is null, an error will occur.

## Solution

The `bugSolution.as` file demonstrates a solution to the problem by checking if `param1` is null before accessing its properties.  This prevents the null object reference error.