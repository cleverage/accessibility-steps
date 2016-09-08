---
id:         10
priority:   Error
topic:      HTML
selector:   frame[title]
status:     not started
---

# When you provide a title attribute for a frame element, do not leave it empty

## Purpose

Permettre la restitution d'un contenu décrivant la fonction et/ou le contenu de l'élément.

## Technical solution

Ajouter un contenu à l'attribut `title` des éléments `<frame>` permettant de connaître la fonction ou le contenu de la `<frame>`. Exemple : `<frame title='navigation src='...' principale'></frame>`.

## Control method

Inspecter le code afin de vérifier la présence de contenu sur les attributs title des éléments `<frame>`.

