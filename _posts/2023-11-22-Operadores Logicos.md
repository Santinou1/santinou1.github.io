---
layout: single
title: Operadores Logicos
date: 2023-11-22
classes: wide
header:
  teaser: "/assets/roadmap.webp"
categories:
  - slae
  - infosec
tags:
  - Introduccion a Python
  - Operadores Logicos
  - Dia 4
---

Se utilizan para combinar dos condiciones y formar una condicion compleja.

Por ejemplo "and" se va a completar cuando dos condiciones son verdaderas

```python
a=3
b=3

#Ejemplos AND

print(a==3 and b==2)
print(a==3 and b==3)
print(a!=3 and b==3)

#Ejemplos OR

print(a!=3 or b==1)
print(a==21 or b==3)

#Ejemplos not

print(not a==3)
print(not a!=3)
```