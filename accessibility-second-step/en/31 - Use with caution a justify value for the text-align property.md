---
id:         31
priority:   Risk
topic:      CSS
selector:   text-align
status:     not started
---

# Use with caution a justify value for the text-align property

## Purpose

Favoriser le parcours oculaire des utilisateurs lorsque les yeux reviennent à la ligne en conservant les différences de longueur de ligne qui, de fait, serviront de repère visuel.

## Technical solution

Remplacer la valeur `justify` par `left`, `right` ou `center`.

## Control method

Inspecter les styles pour vérifier l'absence de la valeur `justify` pour la propriété `text-align`.
