---
id:         3
priority:   Risk
topic:      HTML
selector:   a[target=blank]
status:     not started
---

# Use with caution the target attribute with a _blank value for an a element

## Purpose

Permettre à l'utilisateur de prévoir le comportement des liens qui ouvrent une nouvelle fenêtre.

## Technical solution

Ne pas utiliser l'attribut target ou : Indiquer le comportement du lien dans le libellé du lien (contenu de l'élément `<a>`) ou dans l'attribut `title`. Exemple : `<a href="http://www.google.fr" target="_blank">Site de google (nouvelle fenêtre)</a>` Exemple : `<a href=" http://www.google.fr" target="_blank" title="Site de google (nouvelle fenêtre)">Site de google</a>` Avertissement : le contenu de l'attribut title doit reprendre également le libellé du lien. (exemple incorrect : `<a href=" http://www.google.fr" target="_blank" title="nouvelle fenêtre">Site de google</a>`).

## Control method

Inspecter le lien pour vérifier la présence d'un avertissement dans le libellé ou dans l'attribut `title` lorsque `target` est utilisé.
