# CSS `calc()` Calculation Errors

This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to order of operations, unit mismatches, or nested expression errors. The `bug.css` file contains code exhibiting this problem, while `bugSolution.css` provides the corrected version.

**Problem:** The `calc()` function doesn't always behave intuitively.  Subtracting percentages from pixel values directly often fails, and nested expressions require careful attention to unit consistency and parenthesis balancing.

**Solution:** Ensure that units are consistent within each `calc()` expression. Use parentheses to explicitly control the order of operations, and break down complex calculations into smaller, more manageable parts for clarity and to avoid errors.

See the CSS files for specific code examples and solutions.