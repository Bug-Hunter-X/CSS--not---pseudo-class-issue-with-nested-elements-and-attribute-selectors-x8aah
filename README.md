# CSS :not() Pseudo-class Issue with Nested Elements and Attribute Selectors

This repository demonstrates a subtle bug involving the unexpected behavior of the CSS `:not()` pseudo-class when used with attribute selectors within nested elements.

## Bug Description

The provided CSS code intends to style nested `div` elements based on the presence or absence of specific attributes.  However, the `:not()` selector appears to be ineffective in certain cases.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`. Compare the buggy CSS and the solution.
3. Create an HTML file with nested divs according to the example in `bug.html`.
4. Link the CSS file to your HTML.
5. Observe the unexpected styling in the buggy CSS, compared to the corrected styling in the solution.

## Solution

The solution involves adjusting the CSS selector to address the specificity issue.  Refer to `bugSolution.css` for the corrected code.

## Additional Notes

This bug highlights the importance of understanding CSS selector specificity and the potential for unexpected behavior when using complex selectors.