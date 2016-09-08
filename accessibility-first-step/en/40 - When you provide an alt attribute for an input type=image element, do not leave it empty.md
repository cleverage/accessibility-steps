---
id:         40
priority:   Error
topic:      HTML
selector:   input[type=image]
status:     not started
---

# When you provide an alt attribute for an input type=image element, do not leave it empty

## Purpose

Eviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action.

## Technical solution

Renseigner le contenu de l'attribut `alt` avec la destination ou la fonction du bouton d'action.

## Control method

Inspecter le code afin de vérifier la présence de contenu dans les attributs alt des éléments `<input type="image" />`.