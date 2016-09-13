---
id:         72
priority:   Error
topic:      HTML
selector:   label
status:     not started
---

# Use the for attribute for every label element

## Purpose

Permettre l'association des étiquettes avec les champs auxquelles elles se rapportent.

## Technical solution

Ajouter un attribut `for` sur l'élément `<label>`. Exemple : `<label for='champ-xxx'>xxx</label>`.

## Control method

Inspecter le code et vérifier la présence de l'attribut `for` dans les éléments `<label>`.
