---
id:         23
priority:   Error
topic:      HTML
selector:   h5
status:     not started
---

# Use a h4, h5 or h6 element as a first heading before a h5 element in the source order

## Purpose

Eviter les trous dans la hiérarchie des titres.

## Technical solution

Précéder chaque élément `<h5>` d'un élément `<h4>`, `<h5>` ou `<h6>`.

## Control method

Extraire la structure des titres et vérifier que chaque élément `<h5>` est précédé d'un élément `<h4>`, `<h5>` ou `<h6>`.

