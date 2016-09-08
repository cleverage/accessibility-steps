---
id:         20
priority:   Error
topic:      HTML
selector:   h2
status:     not started
---

# Use a h1, h2, h3, h4, h5 or h6 element as a first heading before a h2 element in the source order

## Purpose

Eviter les trous dans la hiérarchie des titres.

## Technical solution

Précéder chaque élément `<h2>` d'un élément `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` ou `<h6>`.

## Control method

Extraire la structure des titres et vérifier que chaque élément `<h2>` est précédé d'un élément `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>` ou `<h6>`.


