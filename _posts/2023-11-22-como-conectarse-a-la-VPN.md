---
layout: single
    title: Como conectarse una vpn con Kali Linux
    excerpt: "Un  pequeño apunte para saber como conectarme a una vpn usando openVPN."
date: 2023-11-22
classes: wide
header:
  #teaser: /assets/images/htb-writeup-delivery/delivery_logo.png
  teaser_home_page: true
  #icon: /assets/images/hackthebox.webp
categories:
  - tips
tags:  
  - comandos
---

Con Kali nos conectamos a la vpn simplemente con el comando

"openvpn "archivo.ovpn" "

en mi caso por problemas de virtualizacion y del kali que instale , la version de openvpn era inferior a la actual entonces edite el archivo de la vpn y reemplaze la linea del error.

linea 14 original = data-ciphers AES-256-CBC

linea 14 editada = cipher AES-256-CBC

