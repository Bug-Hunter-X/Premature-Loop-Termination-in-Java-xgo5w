# Premature Loop Termination Bug in Java

This repository demonstrates a common but easily overlooked error: premature loop termination in Java.  The `BuggyLoop.java` file contains code with a `break` statement that unexpectedly terminates a `while` loop before it completes its intended iterations. The `FixedLoop.java` file shows the corrected code.

## Understanding the Problem
The bug occurs due to the placement of the `break` statement.  The loop is intended to iterate from 1 to 10, but the `break` statement is executed when `i` equals 5, halting the loop before its natural conclusion. This can lead to incomplete processing or incorrect results.

## Solution
The `FixedLoop.java` file contains the solution. By removing or relocating the conditional `break` statement, we ensure that the loop executes as intended, iterating through all values from 1 to 10.
