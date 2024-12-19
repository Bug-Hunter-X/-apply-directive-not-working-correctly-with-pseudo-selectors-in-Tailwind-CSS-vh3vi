# Tailwind CSS @apply Directive Bug with Pseudo-selectors

This repository demonstrates a bug in Tailwind CSS where the `@apply` directive does not correctly apply styles when used with pseudo-selectors such as `:hover`, `:focus`, and `:active`.

## Bug Description

When using `@apply` with a utility class containing a pseudo-selector, the styles associated with that pseudo-selector are not applied.

## Solution

The solution is to avoid using the `@apply` directive with pseudo-selectors.  Instead, directly apply the utility classes to the element using the appropriate pseudo-selector syntax.

## How to reproduce the bug

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the button does not change color on hover.

## How to fix the bug

1. Open `bugSolution.html` in your browser.
2. Observe that the button correctly changes color on hover.