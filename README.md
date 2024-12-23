# Javascript Type Coercion Bug

This repository demonstrates a common Javascript bug related to type coercion.  The `foo` function attempts to add a number and a string.  Javascript's loose typing leads to unexpected string concatenation instead of numerical addition.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version using explicit type checking.