# Tailwind CSS Gradient Rendering Issue

This repository demonstrates an uncommon issue encountered when using Tailwind CSS gradients. The problem occurs due to browser inconsistencies in handling gradient direction and color values.  The provided `bug.html` file showcases the erroneous rendering, while `bugSolution.html` offers a solution to mitigate the issue. 

## Problem
The gradient may not render correctly, appear different across browsers, or simply not work as intended due to inconsistencies in browser support for specific CSS gradient features.

## Solution
The solution involves adding fallback styles to handle cases where the primary gradient definition is not supported. This can include providing a solid background color as a fallback or using a different gradient technique.