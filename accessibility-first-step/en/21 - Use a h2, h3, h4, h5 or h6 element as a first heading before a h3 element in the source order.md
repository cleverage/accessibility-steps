---
id:         21
priority:   Error
topic:      HTML
selector:   h3
status:     needs review
---

# Use a h2, h3, h4, h5 or h6 element as a first heading before a h3 element in the source order

## Purpose

Avoid blanks in the title hierarchy.

## Technical solution

Precede each `<h3>` element by a `<h2>`, `<h3>`, `<h4>`, `<h5>` or `<h6>` element.

## Control method

Extract the tree title and check that each `<h3>` element is preceded by a `<h2>`, `<h3>`, `<h4>`, `<h5>` ou `<h6>` element.
