---
id:         5
priority:   Error
topic:      HTML
selector:   meta[http-equiv=refresh]
status:     needs review
---

# Don't use a meta element with an http-equiv attribute and a value equal to refresh

## Purpose

Avoid a refresh of the page that users could not control.

## Technical solution

Avoir pages auto-refresh or provide a refresh system where users are informed of the way it performs and where they can disallow this refresh with the help of the mouse or the keyboard.

## Control method

Inspect the source code to check that the `<meta http-equiv="refresh" />` is not present.
