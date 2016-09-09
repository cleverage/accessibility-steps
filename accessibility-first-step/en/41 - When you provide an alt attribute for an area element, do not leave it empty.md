---
id:         41
priority:   Error
topic:      HTML
selector:   area
status:     not started
---

# When you provide an alt attribute for an area element, do not leave it empty

## Purpose

Eviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action.

## Technical solution

Renseigner le contenu de l'attribut `alt` avec la destination du lien.

## Control method

Inspecter le code afin de vérifier la présence de contenu dans les attributs `alt` des `<area>` ayant un attribut `href`.