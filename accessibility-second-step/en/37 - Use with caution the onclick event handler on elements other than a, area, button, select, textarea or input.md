---
id:         37
priority:   Risk
topic:      JS
selector:   onclick
status:     not started
---

# Use with caution the onclick event handler on elements other than a, area, button, select, textarea or input

## Purpose

Permettre aux utilisateurs de percevoir la nature interactive des éléments et de déclencher les interactions quel que soit leur périphérique d'entrée.

## Technical solution

Ne pas utiliser d'événement `onclick` ou alors seulement sur les éléments `<a>`, `<button>`, `<select>`, `<textarea>` ou `<input>`.

## Control method

Utiliser la page au clavier et à la souris afin de voir si des actions ne sont pas réalisables par l'un ou l'autre des périphériques.
