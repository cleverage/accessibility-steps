---
id:         60
priority:   Error
topic:      HTML
selector:   th[scope]
status:     not started
---

# Don't use a value other than row or col for the scope attribute

## Purpose

Permettre l'association des cellules avec leurs entêtes dans les tableaux de données.

## Technical solution

Utiliser la valeur `row` sur l'attribut `scope` des entêtes de ligne et la valeur `col` sur les entêtes de colonnes.

## Control method

Vérifier dans le code source que les valeurs des attributs `scope` est `row` ou `col`.
