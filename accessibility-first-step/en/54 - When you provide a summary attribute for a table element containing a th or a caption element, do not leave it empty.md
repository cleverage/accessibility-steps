---
id:         54
priority:   Error
topic:      HTML
selector:   table[summary]
status:     not started
---

# When you provide a summary attribute for a table element containing a th or a caption element, do not leave it empty

## Purpose

Permettre l'identification des tableaux de données et la restitution des contenus permettant de les caractériser.

## Technical solution

Inclure un contenu à l'attribut `summary` de l'élément `<table>` lorsqu'il s'agit d'un tableau de données.

## Control method

Vérifier dans le code source la présence de contenu dans les attributs `summary` des éléments `<table>` lorsqu'il s'agit d'un tableau de données.
