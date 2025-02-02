# CSS calc() Unexpected Calculation Results

This repository demonstrates a common issue with CSS's `calc()` function. When combining percentages and pixel values (or other units), the calculation might not produce the expected result, especially if the parent element's dimensions are not clearly defined.

The `bug.css` file shows the problematic code, resulting in an incorrect width calculation. The `bugSolution.css` file offers a solution.