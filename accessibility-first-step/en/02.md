---
id:         2
priority:   Error
topic:      HTML
selector:   html
status:     not started
---

# Don't use wrong attribute syntax or non-conforming element hierarchy inside the html element

## Purpose

Eviter les erreurs d'interprétation et de restitution par les agents utilisateurs et les aides techniques.

## Technical solution

Fermer toutes les balises ouvertes. Ne pas imbriquer de balise de type `block` dans les balises de type `inline`. Utiliser des syntaxes et des valeurs d'attribut conformes en fonction de la DTD déclarée.

## Control method

Vérifier la conformité des imbrications de balises et des syntaxes et valeurs d'attribut.

