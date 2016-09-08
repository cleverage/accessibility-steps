---
id:         65
priority:   Error
topic:      HTML
selector:   td[headers]
status:     not started
---

# Don't use for a headers element a value which matches an id attribute used for a td of the table element

## Purpose

Eviter l'utilisation d'éléments obsolètes que les agents utilisateurs de sauraient pas interpréter.

## Technical solution

Utiliser l'élément `<pre>` au lieu de `<plaintext>`.

## Control method

Inspecter le code source pour vérifier l'absence de l'élément `<plaintext>`.
