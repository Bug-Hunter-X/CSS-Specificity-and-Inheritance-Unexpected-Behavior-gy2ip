# CSS Specificity and Inheritance Issue

This repository demonstrates an uncommon CSS issue related to specificity and inheritance.  The `color` property's inheritance behavior is affected by specificity rules in an unexpected way.

## Bug Description:

A more specific rule is defined for `div p`, however, the `inherit` keyword causes the style to inherit from the parent div element, rather than respecting the more specific rule. This contrasts with typical CSS specificity behavior.

## Bug Reproduction Steps:

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`.
3. You'll observe the unexpected inheritance in `bug.css`.
4. The solution in `bugSolution.css` demonstrates a workaround using explicit color declaration.

## Solution:

The solution involves using explicit color declarations instead of relying on inheritance to ensure the desired outcome. See the corrected `bugSolution.css` for details.

This example highlights the importance of understanding CSS specificity and how inheritance interacts with it. Carefully review your CSS to avoid similar unexpected behaviors.