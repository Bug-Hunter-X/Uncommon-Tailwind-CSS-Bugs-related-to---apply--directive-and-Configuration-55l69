# Uncommon Tailwind CSS Bugs
This repository demonstrates some uncommon bugs encountered when using Tailwind CSS, specifically focusing on issues related to the `@apply` directive and configuration problems.  These issues are often more difficult to debug than typical syntax errors.

## Bug 1: `@apply` Directive Issues
The `bug.js` file showcases a scenario where `@apply` is used with a class that doesn't exist or has a typo.  This results in the expected styles not being applied.

## Bug 2: Conflicting Utility Classes
Another common problem is when using multiple conflicting utility classes within the same `@apply` directive. This can lead to unexpected visual results due to the order of application and how styles overwrite each other. This is demonstrated within `bug.js` file.

## Bug 3: `tailwind.config.js` Misconfiguration
Incorrect settings within `tailwind.config.js` can interfere with `@apply` directives. The `bug.js` file shows an example where base styles conflict with `@apply` application.

## Solutions
The `bugSolution.js` file provides solutions to the bugs demonstrated in `bug.js` by fixing typos, resolving conflicting classes, and correctly configuring `tailwind.config.js` to avoid style conflicts.  It shows best practices when using `@apply`.  Remember to check your `tailwind.config.js` for correct purge settings and ensure that all used classes are defined.