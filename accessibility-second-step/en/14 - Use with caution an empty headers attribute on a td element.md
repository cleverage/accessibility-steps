---
id:         14
priority:   Risk
topic:      HTML
selector:   td[headers]
status:     not started
---

# Use with caution an empty headers attribute on a td element

## Purpose

Permettre l'association des cellules avec leurs entêtes dans les tableaux de données.

## Technical solution

Renseigner les attributs `headers` des éléments `<td>` avec les valeurs des attributs id des entêtes associées.

## Control method

Vérifier dans le code source la présence d'un contenu dans les attributs `headers` des éléments `<td>`.
