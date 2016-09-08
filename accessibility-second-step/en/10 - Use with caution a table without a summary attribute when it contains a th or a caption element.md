---
id:         10
priority:   Risk
topic:      HTML
selector:   table
status:     not started
---

# Use with caution a table without a summary attribute when it contains a th or a caption element

## Purpose

Permettre l'identification des tableaux de données et la restitution des contenus permettant de les caractériser.

## Technical solution

Ajouter l'attribut `summary` sur l'élément `<table>` lorsqu'il s'agit d'un tableau de données. Exemple : `<table summary='... '>`

## Control method

Vérifier dans le code source la présence de l'attribut `summary` sur les éléments `<table>` lorsqu'il s'agit d'un tableau de données.
