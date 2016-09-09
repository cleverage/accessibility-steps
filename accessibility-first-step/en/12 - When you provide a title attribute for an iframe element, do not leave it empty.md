---
id:         12
priority:   Error
topic:      HTML
selector:   iframe[title]
status:     needs review
---

# When you provide a title attribute for an iframe element, do not leave it empty

## Purpose

Allow the restitution of a content describing the function and/or content of the element.

## Technical solution

Add a content to the `title` attribute on the `<iframe>` elements.

## Control method

Inspect the source code in order to checck if a content is present in the `title` attributes of the `<iframe>` elements.

