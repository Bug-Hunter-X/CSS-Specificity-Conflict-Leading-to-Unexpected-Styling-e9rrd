# CSS Specificity Conflict Bug

This repository demonstrates a common issue in CSS: unexpected styling behavior due to specificity conflicts. The `bug.css` file contains CSS code that showcases this problem, while `solution.css` provides a fix using more efficient selector techniques. This helps in understanding how specificity affects styling and how to approach such conflicts in complex CSS projects.

## Bug Description:
The bug arises from the conflict between the specificity of the selectors `.myClass p` and `#myDiv p`. The latter, due to ID selector's high specificity, overrides the styling of the former even though it's declared later in the stylesheet.  This leads to the text appearing red instead of the expected blue. 

## Solution:
The solution involves understanding and leveraging CSS specificity rules effectively. In `solution.css`, we explore different techniques to resolve the conflict in a cleaner and maintainable way.