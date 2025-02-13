# JavaScript Loose Comparison Bug

This repository demonstrates a common error in JavaScript related to loose comparison when dealing with null values.  The `foo` function intends to add two numbers but prematurely returns 0 if either argument is null.  This is due to the loose comparison (`===`) potentially causing unexpected behavior.  The solution showcases a more robust approach.

## How to Reproduce

1. Clone this repository.
2. Run `node bug.js` to observe the unexpected behavior.
3. Run `node bugSolution.js` to see the corrected behavior.

## Solution

The solution uses strict null checks to avoid unintended consequences from loose comparisons.