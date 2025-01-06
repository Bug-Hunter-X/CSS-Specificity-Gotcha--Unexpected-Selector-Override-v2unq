# CSS Specificity Gotcha: Unexpected Selector Override

This repository demonstrates a subtle bug related to CSS specificity. The bug showcases how a seemingly less important CSS rule can unexpectedly override another due to its specificity.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file provides a solution to resolve the unexpected behavior.

The problem lies in understanding how CSS selector specificity works. A more specific selector overrides a less specific one, even if the less specific one appears later in the stylesheet.  This behavior is often a source of unexpected styling issues in complex CSS projects.