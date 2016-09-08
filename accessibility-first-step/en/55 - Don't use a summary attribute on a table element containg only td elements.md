---
id:         55
priority:   Error
topic:      HTML
selector:   table[summary]
status:     not started
---

# Don't use a summary attribute on a table element containg only td elements

## Purpose

Permettre aux utilisateurs de différencier les tableaux de données des tableaux de mise en page en n'utilisant pas les caractéristiques spécifiques aux premiers dans les seconds.

## Technical solution

Ne pas utiliser d'attribut `summary` dans les tableaux de mis en page.

## Control method

Vérifier l'absence d'attribut `summary` dans les tableaux de mise en page.
