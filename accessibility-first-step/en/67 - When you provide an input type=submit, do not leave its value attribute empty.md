---
id:         67
priority:   Error
topic:      HTML
selector:   input[type=submit]
status:     not started
---

# When you provide an input type=submit, do not leave its value attribute empty

## Purpose

Eviter à l'utilisateur d'avoir des éléments interactifs dont il ne peut connaitre la destination ou l'action.

## Technical solution

Mettre le texte correspondant à l'action associée dans l'attribut `value`. Exemple : `<input type="submit" value="envoyer le message">`

## Control method

Vérifier dans le code source la présence d'un contenu dans les attributs `value` des éléments `<input type="submit" />`.
