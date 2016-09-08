---
id:         2
priority:   Risk
topic:      HTML
selector:   p
status:     not started
---

# Use with caution successive p elements whose contents start with -, –, —, * ou •

## Purpose

Permettre la restitution de la nature des contenus (ici une liste de définition) aux utilisateurs qui ne perçoivent pas la mise en page originale. Eviter l'utilisation d'élément en fonction de la manière dont ils sont restitués visuellement.

## Technical solution

Utiliser les éléments `<ul>` et `<li>` pour baliser les listes.

## Control method

Repérer visuellement les listes et vérifier que les éléments `<ul>` et `<li>` sont utilisés.