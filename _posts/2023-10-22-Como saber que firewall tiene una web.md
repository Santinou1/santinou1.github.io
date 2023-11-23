---
layout: single
title: Trabajo practico 1
date: 2023-10-22
classes: wide
header:
  teaser: /assets/images/slae32.png
categories:
  - slae
  - infosec
tags:
  - redes
  - introduccion a redes
  - tp
  - firewall
  - Ciberseguridad EducacionIT
  - Dia 3
---

**COMO PODEMOS SABER O técnicas para descubrir si una pagina web tiene un waf de protección, y como saber que solución o marca es ese waf ?**


Primero para visualizar el firewall de una pagina por comodidad me gusta ver la ip de la pagina en ves del ddns.
Para saber la ip de un dns se puede usar el comando

```
nslookup argentina.gob.ar
```


![[Pasted image 20231122124818.png]](../assets/images/img-tp-22-11/Pasted%20image%2020231122124818.png)

ahi podemos ver la ip del dns.

Posteriormente vamos a utilizar una herramienta que viene por defecto en kali linux que es **wafw00f**

la sintaxis seria
```
wafw00f 104.26.5.183
```


Y haciendo eso ya podriamos visualizar el firewall.

![[Pasted image 20231122130832.png]](../assets/images/img-tp-22-11/Pasted%20image%2020231122130832.png)

Sabiendo el firewall podemos buscar las vulnerabilidades en google e intentar bypassearlo.

