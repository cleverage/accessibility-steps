---
id:         6
priority:   Risk
topic:      HTML
selector:   img[alt]
status:     not started
---

# Use with caution a non-empty alt attribute on an img element which is a descendant of a element containing text

## Purpose

Permettre d'éviter la redondance lorsqu'un lien est composé à la fois de texte et d'une image.

## Technical solution

Mettre un `alt=""` sur l'élément `<img>` lorsque ce dernier est inclus dans un lien textuel dont le libellé permet déjà de connaître la destination du lien.

## Control method

Inspecter le code afin de vérifier que l'attribut `alt` des images incluses dans des liens textuel est vide ou qu'il vient bien compléter un contenu textuel afin de rendre le lien plus explicite.
