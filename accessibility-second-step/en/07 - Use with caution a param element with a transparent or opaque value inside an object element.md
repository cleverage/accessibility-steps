---
id:         7
priority:   Risk
topic:      HTML
selector:   object
status:     not started
---

# Use with caution a param element with a transparent or opaque value inside an object element

## Purpose

Permettre la restitution des éléments multimédia au aides techniques.

## Technical solution

Lorsque le contenu de l'élément `<object>` doit pouvoir être lu par une aide technique, utiliser la valeur `window` pour le paramètre `wmode` ou le supprimer. Lorsque le contenu est uniquement décoratif vous pouvez laisser l'attribut `wmode` `transparent` ou `opaque`.

## Control method

Inspecter le code source pour vérifier la valeur de l'attribut `wmode` sur les éléments `<object>`.
