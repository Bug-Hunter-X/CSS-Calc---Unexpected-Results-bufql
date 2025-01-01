# CSS Calc() Unexpected Results

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The problem arises from inconsistencies in units or the order of operations within the calculation, leading to unexpected layout behavior. The `bug.css` file shows the problematic code, and `bugSolution.css` offers a corrected version.

The issue is particularly noticeable when combining percentages and fixed-unit values within the same `calc()` expression, which can result in incorrect sizing and layout discrepancies. 