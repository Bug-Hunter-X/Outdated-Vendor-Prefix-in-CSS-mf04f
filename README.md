# Outdated Vendor Prefix in CSS Bug Report

This repository demonstrates a common CSS bug involving the use of outdated vendor prefixes.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.  Unnecessary vendor prefixes can lead to increased file size and potential rendering inconsistencies. Modern browsers generally support standard CSS properties without prefixes, so removing them is best practice for clean and efficient code.

## How to Reproduce
1. Open `bug.html` in a modern browser.
2. Observe the element with the outdated styling.
3. Compare its rendering with the corrected version in `bugSolution.html`.