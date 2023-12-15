---
layout: single
title: return Python
date: 2023-12-12
classes: wide
header:
  teaser: "/assets/roadmap.webp"
categories:
  - slae
  - infosec
tags:
  - Introduccion a Python
  - Return
  - Dia 9
---

**return expr**

Las funciones opcionalmente pueden devolver un valor o expresión que puede ser utilizado por el programa que invoca la ejecución de la función.

La instrucción **return** finaliza la ejecución y devuelve el valor de la expresión.


Utilizando la funcion sumar escribir un programa que permita ingresar tres numeros e imprima si la suma de los dos primeros es mayor que al tercero.


```python
def sumar(n1,n2):
    return n1+n2

a=int(input("Decime el primer valor..."))
b=int(input("Decime el segundo valor..."))
c=int(input("Decime el tercer valor..."))

  

if sumar(a,b)>c:
    print("es mayor")
else:
    print("es menor")
```

