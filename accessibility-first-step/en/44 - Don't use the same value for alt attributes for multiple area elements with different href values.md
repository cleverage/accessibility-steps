---
id:         44
priority:   Error
topic:      HTML
selector:   area[alt]
status:     not started
---

# Don't use the same value for alt attributes for multiple area elements with different href values

## Purpose

Permettre aux utilisateurs de distinguer les liens qui mènent à des adresses différentes.

## Technical solution

Indiquer dans chaque attribut `alt` un contenu permettant de comprendre la destination du lien.

## Control method

Inspecter le code afin de vérifier que les contenus sont différents.
