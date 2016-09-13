---
id:         26
priority:   Error
topic:      HTML
selector:   li
status:     not started
---

# When you provide a li element, do not leave it empty

## Purpose

Permettre la restitution sans erreur du nombre d'éléments composant une liste. Eviter l'utilisation d'éléments à des fins de présentation.

## Technical solution

Supprimer les éléments `<li>` qui ne possèdent pas de contenu. Utiliser les propriétés des feuilles de styles `margin` et `padding` pour déterminer les écarts entres les différents éléments.

## Control method

Vérifier que le contenu de l'élément `<li>` n'est pas vide.

