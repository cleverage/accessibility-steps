---
id:         20
priority:   Error
topic:      HTML
selector:   h2
status:     needs review
---

# Use a h1, h2, h3, h4, h5 or h6 element as a first heading before a h2 element in the source order

## Purpose

Avoid blanks in the title hierarchy.

## Technical solution

Precede each `<h2>` element by a `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` or `<h6>` element.

## Control method

Extract the tree title and check that each `<h2>` element is preceded by a  `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` ou `<h6>` element.
