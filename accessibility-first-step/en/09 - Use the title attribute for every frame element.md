---
id:         9
priority:   Error
topic:      HTML
selector:   frame
status:     needs review
---

# Use the title attribute for every frame element

## Purpose

Allow the restitution of a content describing the function and/or the content of the element.

## Technical solution

Add a `title` attribut on every `<frame>` element, .e.g. `<frame title='...' src='...'></frame>`.

## Control method

Inspect the source code to check the presence of a `title` attribute on every `<frame>` element.
