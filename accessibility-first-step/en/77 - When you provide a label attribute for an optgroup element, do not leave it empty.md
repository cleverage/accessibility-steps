---
id:         77
priority:   Error
topic:      HTML
selector:   optgroup[label]
status:     not started
---

# When you provide a label attribute for an optgroup element, do not leave it empty

## Purpose

Permettre la distinction des différents groupes formés.

## Technical solution

Déterminer le nom du groupe formé par `<optgroup>` et renseigner l'attribut `label` avec ce nom.

## Control method

Vérifier que le contenu des attributs `label` des éléments `<optgroup>` n'est pas vide.
