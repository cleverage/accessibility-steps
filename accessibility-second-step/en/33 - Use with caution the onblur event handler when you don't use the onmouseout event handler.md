---
id:         33
priority:   Risk
topic:      JS
selector:   onblur
status:     not started
---

# Use with caution the onblur event handler when you don't use the onmouseout event handler

## Purpose

Permettre un comportement équivalent et/ou l'accès à une information équivalente quel que soit le périphérique d'entrée des utilisateurs.

## Technical solution

Lors de l'utilisation de l'événement `onblur`, inclure un comportement équivalent sur l'événement `onmouseout` ou prévoir un autre élément permettant de réaliser la même action via la souris.

## Control method

Utiliser la page au clavier et à la souris afin de voir si des actions sont déclenchées uniquement à l'aide du clavier.
