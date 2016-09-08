---
id:         40
priority:   Risk
topic:      JS
selector:   onfocus
status:     not started
---

# Use with caution the onfocus event handler to trigger the blur method

## Purpose

Conserver le focus sur les éléments le recevant.

## Technical solution

Supprimer l'appel à la méthode `blur()`.

## Control method

Naviguer au clavier dans la page afin de voir si un élément ne perd pas directement le `focus` alors qu'il le reçoit.