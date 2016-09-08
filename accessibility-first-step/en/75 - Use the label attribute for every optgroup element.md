---
id:         75
priority:   Error
topic:      HTML
selector:   optgroup
status:     not started
---

# Use the label attribute for every optgroup element

## Purpose

Permettre la restitution d'un titre au groupe formé par `<optgroup>`.

## Technical solution

Ajouter un attribut `label` aux éléments `<optgroup>`. Exemple : `<optgroup label='france'>...</optgroup>`.

## Control method

Inspecter le code source pour vérifier que chaque élément `<optgroup>` contient un attribut `label`.
