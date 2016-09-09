---
id:         8
priority:   Error
topic:      HTML
selector:   dir
status:     needs review
---

# Don't use a value other than ltr, rtl or empty for the dir attribute

## Purpose

Allow assistive technologies to adapt to the document's language.

## Technical solution

When the `dir` attribute is used, his value must be `rtl`, `ltr` or empty.

## Control method

Inspect the source code to check that the value of the `dir` attribute is `rtl`, `ltr` or empty.
