---
id:         5
priority:   Error
topic:      HTML
selector:   meta[http-equiv=refresh]
status:     not started
---

# Don't use a meta element with an http-equiv attribute and a value equal to refresh

## Purpose

Eviter aux utilisateurs un rechargement de la page qu'il ne pourrait pas maîtriser.

## Technical solution

Eviter les rechargements automatiques des pages ou utiliser un système de rechargement où les utilisateurs sont informés du fonctionnement et où ils peuvent désactiver ce rechargement avec la souris et avec le clavier.

## Control method

Inspecter le code source pour vérifier l'absence de l'élément `<meta http-equiv="refresh" />`.



