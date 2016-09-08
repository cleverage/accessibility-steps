---
id:         30
priority:   Risk
topic:      CSS
selector:   outline
status:     not started
---

# Use with caution a 0 or none value for the outline property

## Purpose

Ne pas supprimer le repère visuel que constitue l'encadré pris par les éléments interactifs lorsqu'ils reçoivent le focus.

## Technical solution

Ne pas utiliser la propriété `outline` ou alors, seulement pour accentuer la manière dont sont restitués les éléments interactifs lorsqu'ils reçoivent le focus. Exemple : `a:focus, input:focus, select:focus, textarea:focus { outline: 3px solid red !important; }`.

## Control method

Inspecter les styles pour vérifier l'absence des valeurs `0` et `none` pour la propriété `outline`.