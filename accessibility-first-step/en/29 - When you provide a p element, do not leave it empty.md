---
id:         29
priority:   Error
topic:      HTML
selector:   p
status:     not started
---

# When you provide a p element, do not leave it empty

## Purpose

Eviter l'utilisation d'éléments à des fins de présentation.

## Technical solution

Supprimer les éléments `<p>` qui ne possèdent pas de contenu. Utiliser les propriétés des feuilles de styles `margin` et `padding` pour déterminer les écarts entres les différents éléments.

## Control method

Vérifier que le contenu des éléments `<p>` n'est pas vide.

