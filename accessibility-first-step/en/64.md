---
id:         64
priority:   Error
topic:      HTML
selector:   plaintext
status:     not started
---

# Don't use the plaintext element

## Purpose

Eviter l'utilisation d'éléments obsolètes que les agents utilisateurs de sauraient pas interpréter.

## Technical solution

Utiliser l'élément pre au lieu de `<plaintext>`.

## Control method

Inspecter le code source pour vérifier l'absence de l'élément `<plaintext>`.