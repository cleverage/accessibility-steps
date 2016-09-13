---
id:         58
priority:   Error
topic:      HTML
selector:   table
status:     not started
---

# Use at least one th element inside a table element with a caption element or a non-empty summary attribute

## Purpose

Permettre l'identification des tableaux de données et la restitution des contenus permettant de les caractériser.

## Technical solution

Modifier le code de manière à utiliser l'élément `<th>` à la place de l'élément `<td>` afin de déclarer les entêtes des tableaux de données. Si c'est un tableau de mise en forme supprimer le `<caption>` ou le `summary` non vide.

## Control method

Vérifier dans le code source la présence d'élément `<th>` dans les éléments `<table>` lorsqu'il s'agit d'un tableau de données.
