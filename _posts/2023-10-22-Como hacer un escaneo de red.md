---
layout: single
title: Escanear redes con IP Scanner
date: 2023-10-22
classes: wide
header:
  teaser: /assets/images/slae32.png
categories:
  - slae
  - infosec
tags:
  - IP-Scanner
  - Ciberseguridad EducacionIT
  - Dia 3
---

Como anteriormente vimos en mi blog.
Estuve hablando de los ip, de la mascara de red, de la mac etc.
Había comentado que la IP es la mascara de red + el dispositivo unico.
Ahora bien, sabiendo eso podemos hacer un análisis de red para ver si hay una ip desconocida dentro de nuestro wifi.

#### Como lo hacemos?
Instalamos el programa  "Ip Scanner" , y en los parámetros vamos a poner nuestra ip y en el ultimo octeto, vamos a poner 1-255 haciendo referencia a todos los dispositivos únicos que puedan existir.

Y posteriormente a eso en el escáner quedaría algo así.

![[Pasted image 20231122093118.png]](../assets/images/img-introduccion-a-ciberseguridad/Pasted%20image%2020231122093118.png)

