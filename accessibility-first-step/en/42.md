---
id:         42
priority:   Error
topic:      HTML
selector:   img[alt]
status:     not started
---

# If an img element is a child of an a element with text, do not use the same text for its alt attribute as the text inside the a element

## Purpose

Eviter à l'utilisateur d'avoir une information qui lui est restituée plusieurs fois.

## Technical solution

Utiliser un attribut `alt=""` sur l'image contenu dans un lien contenant également du texte faisant office d'intitulé.

## Control method

Inspecter le code afin de vérifier que la valeur de l'attribut `alt` est vide (`alt=""`) sur les éléments `<img>` contenu dans des liens contenant également du texte faisant office d'intitulé de lien.