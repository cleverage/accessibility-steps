---
id:         63
priority:   Error
topic:      HTML
selector:   td
status:     not started
---

# Use a headers attribute on every td element if the corresponding th element has an id attribute

## Purpose

Permettre l'association des cellules avec leurs entêtes dans les tableaux de données.

## Technical solution

Utiliser un attribut `headers` sur les cellules `<td>` des tableaux de données dont les entêtes (`<th>`) contiennent un attribut `id`.

## Control method

Vérifier dans le code source la présence de l'attribut `headers` dans les éléments `<td>` des tableaux de données dont les entêtes (`<th>`) contiennent un attribut `id`.
