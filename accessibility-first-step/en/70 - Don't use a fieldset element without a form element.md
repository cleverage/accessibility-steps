---
id:         70
priority:   Error
topic:      HTML
selector:   fieldset
status:     not started
---

# Don't use a fieldset element without a form element

## Purpose

Eviter l'utilisation d'une structuration non appropriée pour regrouper des éléments html.

## Technical solution

Privilégier les éléments de structuration sémantique tel que `<section>`, `<article>`, `<aside>` pour structurer les blocs d'informations.

## Control method

Inspecter le code afin de vérifier qu'un élément `<fieldset>` n'est pas utilisé en dehors de l'élément `<form>`.
