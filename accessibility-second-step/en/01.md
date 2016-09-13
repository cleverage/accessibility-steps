---
id:         1
priority:   Risk
topic:      HTML
selector:   div
status:     not started
---

# Use with caution successive div elements whose contents start with -, –, —, * or •

## Purpose

Permettre la restitution de la nature des contenus (ici une liste) et de leurs caractéristiques (ici le nombre d'item de cette liste) aux utilisateurs qui ne perçoivent pas la mise en page originale. Ainsi, la transmission uniquement visuelle d'une information sémantique est évitée.

## Technical solution

Utiliser les éléments `<ul>` et `<li>` pour baliser les listes.

## Control method

Repérer visuellement les listes et vérifier que les éléments `<ul>` et `<li>` sont utilisés.
