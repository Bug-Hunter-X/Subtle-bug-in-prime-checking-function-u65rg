# Subtle Bug in Prime Checking Function

This repository demonstrates a subtle bug in a JavaScript function designed to check if a number is prime. The function incorrectly handles the input 1, resulting in unexpected output.

## Bug Description

The `checkIfPrime` function fails to explicitly handle the case where the input number is 1. While 1 is not a prime number, the function's logic doesn't correctly identify it as non-prime.

## Bug Solution

The bug is fixed by explicitly adding a check for the input number being equal to 1, returning `false` in that case.

## How to Reproduce

1. Clone this repository.
2. Run `bug.js`.
3. Observe the incorrect output for the input 1.
4. Run `bugSolution.js` to see the corrected output.
