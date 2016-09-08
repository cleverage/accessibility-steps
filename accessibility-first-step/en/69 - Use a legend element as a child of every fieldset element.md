---
id:         69
priority:   Error
topic:      HTML
selector:   fieldset
status:     not started
---

# Use a legend element as a child of every fieldset element

## Purpose

Permettre la restitution d'un titre au groupe formé par `<fieldset>`.

## Technical solution

Utiliser l'élément `<legend>` juste après l'élément `<fieldset>` ou remplacer l'élément `<fieldset>` par un `<div>`.

## Control method

Inspecter le code source pour vérifier qu'un élément `<legend>` suit chaque élément `<fieldset>`.
