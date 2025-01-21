# Unexpected String Concatenation in JavaScript

This repository demonstrates a common yet easily overlooked error in JavaScript: the unexpected concatenation of numbers and strings.

## The Bug

The `foo` function intends to add two numbers. However, when one of the inputs is a string, JavaScript performs string concatenation instead of numerical addition.

## The Solution

The solution involves type checking or explicit type conversion to ensure both inputs are numbers before performing the addition operation.

## How to Reproduce

1. Clone this repository.
2. Run the `bug.js` file. Observe the unexpected output.
3. Run the `bugSolution.js` file to see the corrected code.