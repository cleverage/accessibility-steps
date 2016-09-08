---
id:         4
priority:   Risk
topic:      HTML
selector:   area[target=blank]
status:     not started
---

# Use with caution the target attribute with a _blank value for an area element

## Purpose

Permettre à l'utilisateur de prévoir le comportement des liens qui ouvrent une nouvelle fenêtre.

## Technical solution

Ne pas utiliser l'attribut `target="_blank"` ou indiquer l'ouverture dans une nouvelle fenêtre dans le contenu de l'attribut `alt` associé à l'élément `<area>`. Exemple : `<area alt='France – nouvelle fenêtre'></area>`.

## Control method

Inspecter le contenu de l'alternative aux zones `<area>` pour vérifier la présence d'un avertissement lorsque `target` est utilisé.
