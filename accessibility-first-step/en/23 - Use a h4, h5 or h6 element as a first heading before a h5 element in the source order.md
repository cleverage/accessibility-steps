---
id:         23
priority:   Error
topic:      HTML
selector:   h5
status:     needs review
---

# Use a h4, h5 or h6 element as a first heading before a h5 element in the source order

## Purpose

Avoid blanks in the title hierarchy.

## Technical solution

Precede each `<h5>` element by a `<h4>`, `<h5>` or `<h6>` element.

## Control method

Extract the tree title and check that each `<h5>` element is preceded by a `<h4>`, `<h5>` ou `<h6>` element.
