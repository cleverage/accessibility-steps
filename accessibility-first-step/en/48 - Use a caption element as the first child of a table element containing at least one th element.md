---
id:         48
priority:   Error
topic:      HTML
selector:   table
status:     not started
---

# Use a caption element as the first child of a table element containing at least one th element

## Purpose

Permettre l'identification des tableaux de données et la restitution des contenus permettant de les caractériser.

## Technical solution

Positionner un élément `<caption>` tout de suite après l'élément `<table>` lorsqu'il s'agit d'un tableau de données.

## Control method

Vérifier dans le code source que les éléments `<table>` sont directement suivi d'un élément `<caption>` lorsqu'il s'agit d'un tableau de données.
