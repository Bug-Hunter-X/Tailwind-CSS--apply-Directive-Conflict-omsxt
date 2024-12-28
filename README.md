# Tailwind CSS @apply Directive Conflict

This repository demonstrates a common issue encountered when using Tailwind CSS's `@apply` directive: conflicts with pre-existing styles. The `@apply` directive, while convenient, can lead to unpredictable behavior if not carefully managed. 

## Problem
The `bug.css` file shows a situation where `@apply` is used in a class that already has inline styles. This conflict can result in the styles applied via `@apply` being overridden, ignored, or causing unexpected cascading effects.

## Solution
The `bugSolution.css` file provides a solution for this. The key is to be mindful of the order of styles and to separate concerns where necessary, often involving refactoring for more clarity.