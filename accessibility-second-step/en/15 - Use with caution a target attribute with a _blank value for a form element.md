---
id:         15
priority:   Risk
topic:      HTML
selector:   form[target=blank]
status:     not started
---

# Use with caution a target attribute with a _blank value for a form element

## Purpose

Permettre à l'utilisateur de prévoir le comportement des formulaires qui ouvrent une nouvelle fenêtre.

## Technical solution

Ne pas utiliser l'attribut `target="_blank"` ou indiquer textuellement l'ouverture dans une nouvelle fenêtre dans le formulaire ou sur le bouton permettant de valider le formulaire. Exemple : `<input type='submit' value='ok' title='Valider la recherche – nouvelle fenêtre' />`

## Control method

Inspecter le formulaire pour vérifier la présence d'un avertissement lorsque `target` est utilisé.
