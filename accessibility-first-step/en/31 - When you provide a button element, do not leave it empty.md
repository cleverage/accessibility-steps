---
id:         31
priority:   Error
topic:      HTML
selector:   button
status:     not started
---

# When you provide a button element, do not leave it empty

## Purpose

Eviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action.

## Technical solution

Mettre du texte dans l'élément button. Exemple : `<button>Passer ma commande</button>`.

## Control method

Vérifier dans le code source qu'il n'y a pas d'élément `<button>` sans contenu textuel.
