---
id:         76
priority:   Error
topic:      HTML
selector:   optgroup[label]
status:     not started
---

# Don't use the same label attribute for different optgroup elements of the same select element

## Purpose

Permettre la distinction des différents groupes formés.

## Technical solution

Déterminer un titre différent pour chaque groupe formé par les éléments `<optgroup>`.

## Control method

Vérifier que le contenu de chaque attribut `label` des éléments `<optgroup>` est différent.
