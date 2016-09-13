---
id:         22
priority:   Error
topic:      HTML
selector:   h4
status:     needs review
---

# Use a h3, h4, h5 or h6 element as a first heading before a h4 element in the source order

## Purpose

Avoid blanks in the title hierarchy.

## Technical solution

Precede each `<h4>` element by a `<h3>`, `<h4>`, `<h5>` or `<h6>` element.

## Control method

Extract the tree title and check that each `<h4>` element is preceded by a `<h3>`, `<h4>`, `<h5>` ou `<h6>` element.
