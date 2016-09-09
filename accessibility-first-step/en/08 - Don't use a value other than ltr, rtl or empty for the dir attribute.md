---
id:         8
priority:   Error
topic:      HTML
selector:   dir
status:     not started
---

# Don't use a value other than ltr, rtl or empty for the dir attribute

## Purpose

Permettre l'adaptation des aides techniques au sens de la langue du document.

## Technical solution

Lorsque l'attribut `dir` est utilisé sa valeur doit être `rtl`, `ltr` ou vide.

## Control method

Inspecter le code afin de vérifier que la valeur de l'attribut dir est bien `rtl`, `ltr` ou vide.

