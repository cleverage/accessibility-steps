---
id:         39
priority:   Risk
topic:      JS
selector:   onfocus
status:     not started
---

# Use with caution the onfocus event handler when you don't use the onmouseover event handler

## Purpose

Permettre un comportement équivalent et/ou l'accès à une information équivalente quel que soit le périphérique d'entrée des utilisateurs

## Technical solution

Lors de l'utilisation de l'événement `onfocus`, inclure un comportement équivalent sur l'événement onmouseover ou prévoir un autre élément permettant de réaliser la même action via la souris.

## Control method

Utiliser la page au clavier et à la souris afin de voir si des actions sont déclenchées uniquement à l'aide du clavier.