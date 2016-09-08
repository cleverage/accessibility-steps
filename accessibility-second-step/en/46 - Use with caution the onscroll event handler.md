---
id:         46
priority:   Risk
topic:      JS
selector:   onscroll
status:     not started
---

# Use with caution the onscroll event handler

## Purpose

Eviter aux utilisateurs l'obligation de posséder un périphérique de pointage tel que la souris et d'avoir la capacité de scroller pour interagir avec le site ou avoir accès à une information.

## Technical solution

Ne pas utiliser l'évènement `onscroll` ou fournir un moyen d'effectuer la même action d'une manière indépendante du périphérique d'entrée.

## Control method

Scroller dans la page afin de voir si des éléments ne sont pas déclenchés lors du scroll.