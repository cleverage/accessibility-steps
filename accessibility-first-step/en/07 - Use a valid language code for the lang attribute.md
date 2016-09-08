---
id:         7
priority:   Error
topic:      HTML
selector:   lang
status:     not started
---

# Use a valid language code for the lang attribute

## Purpose

Permettre la déclaration de la langue du document et l'adaptation des aides techniques à celle-ci.

## Technical solution

Donner une valeur conforme au code de langue dans l'attribut `lang`. Exemple : “fr“ pour le français, “en“ pour l'anglais. Voir http://www.loc.gov/standards/iso639-2/php/code_list.php pour la liste complète des codes de langue.

## Control method

Inspecter le code afin de vérifier la présence d'un code de langue conforme dans les attributs `lang`.

