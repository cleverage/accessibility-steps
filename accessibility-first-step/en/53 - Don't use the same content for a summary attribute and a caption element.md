---
id:         53
priority:   Error
topic:      HTML
selector:   table[summary]
status:     not started
---

# Don't use the same content for a summary attribute and a caption element

## Purpose

Permettre aux utilisateurs de distinguer le sujet d'un tableau de données de la manière dont il est construit.

## Technical solution

Mettre dans l'élément `<caption>` un contenu servant à titrer le tableau et dans l'attribut `summary` un contenu pour décrire l'organisation du tableau.

## Control method

Vérifier que le contenu de l'élément `<caption>` est différent du contenu de l'attribut `summary`.
