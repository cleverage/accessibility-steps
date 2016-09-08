---
id:         29
priority:   Risk
topic:      CSS
selector:   font-size
status:     not started
---

# Use with caution pixel values for the font-size property

## Purpose

Permettre aux utilisateurs d'agrandir le texte avec les zooms textuels des agents utilisateurs.

## Technical solution

Utiliser les unités em, %, ou les mots-clés (large, medium, small, etc.) pour définir les valeurs de la propriété `font-size` pour tous les éléments ou, au minimum, sur les éléments de formulaire.

## Control method

Inspecter les styles destinés à l'affichage à l'écran et vérifier l'absence de l'unité pixel (`px`) dans les valeurs de la propriété `font-size` des éléments de formulaire.
