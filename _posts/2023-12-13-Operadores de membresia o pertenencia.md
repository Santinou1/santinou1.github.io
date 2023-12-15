---
layout: single
title: Operadores de membresia o pertenencia Python
date: 2023-12-12
classes: wide
header:
  teaser: "/assets/roadmap.webp"
categories:
  - slae
  - infosec
tags:
  - Introduccion a Python
  - in
  - Dia 9
---

**expr [not] in coleccion**

Devuelve verdadero si la expresion pertenece a la coleccion.

Para el caso de las tuplas y listas se utiliza el valor; en cambio para los diccionarios se utiliza la clave

###### Ejemplos

```python
diccionario= {"name":"santi",
              "edad":19,
              }

numeros= [1,2,3,4,5]

print("name" in diccionario) # True
print(5 in numeros) # True
print(6 in numeros) # False
```

