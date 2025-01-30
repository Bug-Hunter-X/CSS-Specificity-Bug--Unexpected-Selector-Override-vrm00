# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity. The bug showcases a situation where a more specific selector is unexpectedly overridden by a less specific one due to how specificity is calculated in CSS.

## Bug Description
The bug involves a scenario where multiple CSS rules apply to the same element, with varying levels of specificity.  The selector with higher specificity should generally take precedence. However, a misunderstanding of specificity's calculation can lead to unexpected results.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to examine the CSS code that produces the unexpected behavior.
3. Open the HTML file (you will need to create this HTML file) and observe the rendered output. You will see that the text color is not what would intuitively be expected.

## Solution
The solution involves a better understanding of CSS specificity and modifying the CSS rules to ensure the desired selector takes precedence (see `bugSolution.css`).