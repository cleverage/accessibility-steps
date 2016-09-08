---
id:         30
title:      When you provide an a element, do not leave it empty except if it is used as an anchor
priority:   Error
topic:      HTML
selector:   a
status:     not started
---

## Purpose

Éviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action

## Technical solution

Mettre un libellé dans l'élément <a>. Par exemple : <a href="http://www.google.fr">Site de google</a>

## Control method

Vérifier dans le code source qu'il n'y a pas de liens sans contenu textuel.
