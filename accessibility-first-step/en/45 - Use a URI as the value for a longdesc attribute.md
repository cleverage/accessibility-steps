---
id:         45
priority:   Error
topic:      HTML
selector:   img[longdesc]
status:     not started
---

# Use a URI as the value for a longdesc attribute

## Purpose

Permettre d'associer le contenu d'une description longue à l'image à laquelle il se rapporte.

## Technical solution

Ajouter une url dans l'attribut `longdesc`. Exemple : `<img longdesc="url-de-la-description.html" … >`

## Control method

Inspecter le code et vérifier la présence d'une url dans l'attribut `longdesc`.
