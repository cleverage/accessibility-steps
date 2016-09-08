---
id:         73
priority:   Error
topic:      HTML
selector:   label[for]
status:     not started
---

# When you provide a for attribute for a label element, do not leave it empty

## Purpose

Eviter à l'utilisateur la restitution d'étiquette associée à aucun champ de formulaire.

## Technical solution

Mettre dans l'attribut `for` la valeur de l'identifiant du champ associé au `<label>`.

## Control method

Inspecter le code et vérifier la présence de contenu dans les attributs `for` des éléments `<label>`.
