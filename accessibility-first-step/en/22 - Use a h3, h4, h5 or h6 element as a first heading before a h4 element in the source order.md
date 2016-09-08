---
id:         22
priority:   Error
topic:      HTML
selector:   h4
status:     not started
---

# Use a h3, h4, h5 or h6 element as a first heading before a h4 element in the source order

## Purpose

Eviter les trous dans la hiérarchie des titres.

## Technical solution

Précéder chaque élément `<h4>` d'un élément `<h3>`, `<h4>`, `<h5>` ou `<h6>`.

## Control method

Extraire la structure des titres et vérifier que chaque élément `<h4>` est précédé d'un élément `<h3>`, `<h4>`, `<h5>` ou `<h6>`.

