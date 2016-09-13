---
id:         8
priority:   Risk
topic:      HTML
selector:   embed
status:     not started
---

# Use with caution a wmode attribute with a transparent or opaque value on an embed element

## Purpose

Permettre la restitution des éléments multimédia au aides techniques.

## Technical solution

Lorsque le contenu de l'élément `<embed>` doit pouvoir être lu par une aide technique, utiliser la valeur `window` pour l'attribut `wmode` ou le supprimer. Lorsque le contenu est uniquement décoratif vous pouvez laisser l'attribut `wmode` `transparent` ou `opaque`.

## Control method

Inspecter le code source pour vérifier la valeur de l'attribut `wmode` sur les éléments `<embed>`.

