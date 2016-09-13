---
id:         45
priority:   Risk
topic:      JS
selector:   onmouseover
status:     not started
---

# Use with caution the onmouseover event handler when you don't use the onfocus event handler

## Purpose

Permettre un comportement équivalent et/ou l'accès à une information équivalente quel que soit le périphérique d'entrée des utilisateurs.

## Technical solution

Lors de l'utilisation de l'événement `onmouseover`, inclure un comportement équivalent sur l'événement `onfocus` ou prévoir un autre élément permettant de réaliser la même action via le clavier.

## Control method

Utiliser la page au clavier et à la souris afin de voir si des actions sont déclenchées uniquement à l'aide de la souris.