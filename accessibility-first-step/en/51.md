---
id:         51
priority:   Error
topic:      HTML
selector:   caption
status:     not started
---

# Don't use a caption element in a table element containing only td elements

## Purpose

Permettre la distinction entre les tableaux de données et les tableaux de mise en page.

## Technical solution

Ne pas utiliser d'élément `<caption>` dans les tableau de mise en page. En revanche, dans le cas d'un tableau de données où l'élément `<caption>` serait justifié, utiliser des éléments `<th>` pour signaler les entêtes du tableau.

## Control method

Déterminer la nature du tableau : de mise en page ou de données. S'il s'agit d'un tableau de mise en page, vérifier l'absence de l'élément `<caption>`. S'il s'agit d'un tableau de données, vérifier la présence d'élément `<th>` pour déclarer les entêtes de tableau.
