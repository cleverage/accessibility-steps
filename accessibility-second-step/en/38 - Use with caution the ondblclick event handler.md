---
id:         38
priority:   Risk
topic:      JS
selector:   ondblclick
status:     not started
---

# Use with caution the ondblclick event handler

## Purpose

Eviter aux utilisateurs l'obligation de posséder un périphérique de pointage tel que la souris et d'avoir la capacité à double cliquer pour interagir avec le site.

## Technical solution

Ne pas utiliser l'évènement `ondbclick` ou fournir un moyen d'effectuer la même action d'une manière indépendante du périphérique d'entrée.

## Control method

Utiliser la page au clavier et à la souris afin de voir si des actions ne sont pas réalisables par l'un ou l'autre des périphériques.