---
id:         11
priority:   Risk
topic:      HTML
selector:   table[summary]
status:     not started
---

# Use with caution the same content for multiple summary attributes

## Purpose

Permettre aux utilisateurs de distinguer les données fournies et la manière avec laquelle chaque tableau de données est construit.

## Technical solution

Décrire les données et la manière dont est construit chaque tableau de données et ajouter cette description à l'attribut `summary` des tableaux.

## Control method

Vérifier que le contenu de chaque attribut `summary` est différent.
