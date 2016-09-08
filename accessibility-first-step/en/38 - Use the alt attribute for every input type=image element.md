---
id:         38
priority:   Error
topic:      HTML
selector:   input[type=image]
status:     not started
---

# Use the alt attribute for every input type=image element

## Purpose

Permettre la restitution d'un contenu alternatif aux utilisateurs qui ne peuvent pas percevoir le contenu de l'élément.

## Technical solution

Ajouter l'attribut `alt` sur l'élément. Exemple : `<input type='image' alt='...'/>`.

## Control method

Inspecter le code et vérifier la présence de l'attribut `alt` dans l'élément `<input type="image" />`.