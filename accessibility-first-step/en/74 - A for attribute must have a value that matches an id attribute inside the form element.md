---
id:         74
priority:   Error
topic:      HTML
selector:   label[for]
status:     not started
---

# A for attribute must have a value that matches an id attribute inside the form element

## Purpose

Eviter à l'utilisateur la restitution d'étiquette associée à aucun champ de formulaire.

## Technical solution

Corriger la valeur de l'attribut `for` afin de la faire correspondre au champ associé au `<label>`.

## Control method

Inspecter le code et vérifier que la valeur de l'attribut `for` des éléments `<label>` est égale à la valeur des attributs `id` des champs de formulaire auxquels ils se rapportent.
