# Unexpected Behavior with Spaces in CSS `calc()` Function

This repository demonstrates an uncommon bug related to the use of spaces within the `calc()` function in CSS.  Incorrect spacing can lead to unexpected results or rendering errors.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides the corrected version.

**Problem:** Extra spaces around the `+`, `-`, `*`, and `/` operators inside the `calc()` function can prevent the calculation from working correctly. 

**Solution:** Ensure there are no spaces surrounding the operators within the `calc()` function.  Keep the expression compact.