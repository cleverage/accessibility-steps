---
id:         24
priority:   Error
topic:      HTML
selector:   h6
status:     not started
---

# Use a h5 or h6 element as a first heading before a h6 element in the source order

## Purpose

Eviter les trous dans la hiérarchie des titres.

## Technical solution

Précéder chaque élément `<h6>` d'un élément `<h5>` ou `<h6>`.

## Control method

Extraire la structure des titres et vérifier que chaque élément `<h6>` est précédé d'un élément `<h5>` ou `<h6>`.

