---
id:         32
priority:   Risk
topic:      CSS
selector:   text-indent
status:     not started
---

# Use with caution a negative value for the text-indent property used together with the background-image property on the same selector

## Purpose

Eviter la perte d'information lorsque les images sont désactivés.

## Technical solution

Ne pas associer ces deux propriétés sur le même sélecteur.

## Control method

Inspecter les styles pour vérifier l'absence d'association de ces deux propriétés sur le même sélecteur.
