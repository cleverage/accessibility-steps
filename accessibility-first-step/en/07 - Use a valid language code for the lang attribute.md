---
id:         7
priority:   Error
topic:      HTML
selector:   lang
status:     needs review
---

# Use a valid language code for the lang attribute

## Purpose

Allow the declaration of the document's language and allow assistive technologies to adapt to it.

## Technical solution

Specify a standard value for the language code in the `lang` attribute, e.g. "fr" for french, "en" for english. Refer to the [complete list of language codes](http://www.loc.gov/standards/iso639-2/php/code_list.php).

## Control method

Inspect the source code to check the presence of a standard language code in the `lang` attributes.
