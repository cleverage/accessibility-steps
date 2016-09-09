---
id:         9
priority:   Error
topic:      HTML
selector:   frame
status:     needs review
---

# Use the title attribute for every frame element

## Purpose

Permettre la restitution d'un contenu décrivant la fonction et/ou le contenu de l'élément.

## Technical solution

Ajouter un attribut `title` sur chaque élément `<frame>`. Exemple : `<frame title='...' src='...'></frame>`.

## Control method

Inspecter le code afin de vérifier la présence d'un attribut `title` sur chaque élément `<frame>`.
