---
id:         36
priority:   Risk
topic:      JS
selector:   onchange
status:     not started
---

# Use with caution the onchange event handler with the location object

## Purpose

Eviter aux utilisateurs un changement de contexte sans validation explicite de leur part.

## Technical solution

Prévoir un bouton de validation explicite que l'utilisateur devra déclencher à cette fin pour valider le changement de contexte. Alternativement, il est possible d'informer au préalable les utilisateurs de ce comportement.

## Control method

Utiliser la page au clavier ou à la souris afin de voir si la page est redirigée automatiquement lors du changement dans un élément de formulaire (dans une liste `<select>` par exemple).
