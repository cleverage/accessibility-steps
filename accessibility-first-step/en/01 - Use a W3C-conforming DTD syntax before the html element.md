---
id:         1
title:      Use a W3C-conforming DTD syntax before the html element
priority:   Error
topic:      HTML
selector:   html
---

# Purpose

Allow user agents to correctly interpret the document.

# Technical solution

Place a W3C-conforming DTD as first element of the document. Chose one from this list: http://www.w3.org/QA/2002/04/valid-dtd-list.html

# Control method

Check that the first element in pages is a conform DTD declaration.
