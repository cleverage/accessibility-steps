---
id:         39
priority:   Error
topic:      HTML
selector:   img[alt]
status:     not started
---

# If the img element is the only child of a button or an a element, do not leave its alt attribute empty

## Purpose

Eviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action.

## Technical solution

Renseigner le contenu de l'attribut alt avec la destination du lien ou la fonction du bouton d'action.

## Control method

Inspecter le code afin de vérifier la présence de contenu dans les attributs alt des images et des éléments button.