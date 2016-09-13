---
id:         10
priority:   Error
topic:      HTML
selector:   frame[title]
status:     needs review
---

# When you provide a title attribute for a frame element, do not leave it empty

## Purpose

Allow the restitution of a content describing the function and/or the content of the element.

## Technical solution

Fill the `title` attribute of the `<frame>` elements to understand the function or the content of the `<frame>`, .e.g. `<frame title='main navigation' src='...'></frame>`.

## Control method

Inspect the source code to check if content is present in the `title` attributes of the `<frame>` elements.
