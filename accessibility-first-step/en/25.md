---
id:         25
priority:   Error
topic:      HTML
selector:   dl
status:     not started
---

# Use a dt element as the first child of a dl element

## Purpose

Permettre la restitution de la nature des contenus (ici une liste de définition) aux utilisateurs qui ne perçoivent pas la mise en page originale. Eviter l'utilisation d'élément en fonction de la manière dont ils sont restitués visuellement.

## Technical solution

Utiliser les éléments `<dl>` et `<dt>` et `<dd>` pour baliser les listes de définition.

## Control method

Vérifier dans le code source que chaque élément `<dl>` est immédiatement suivi d'un élément `<dt>`.

