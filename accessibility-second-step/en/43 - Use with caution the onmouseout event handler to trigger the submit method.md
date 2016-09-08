---
id:         43
priority:   Risk
topic:      JS
selector:   onmouseout
status:     not started
---

# Use with caution the onmouseout event handler to trigger the submit method

## Purpose

Eviter aux utilisateurs un changement de contexte sans validation explicite de leur part.

## Technical solution

Prévoir un bouton de validation explicite que l'utilisateur devra déclencher à cette fin pour soumettre un formulaire. Alternativement, il est possible d'informer au préalable les utilisateurs de ce comportement.

## Control method

Utiliser la page à la souris afin de voir si des formulaires sont validés automatiquement lors de la navigation au clavier.