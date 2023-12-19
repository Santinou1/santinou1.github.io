---
layout: single
title: Comandos SQL
date: 2023-12-18
classes: wide
header:
  teaser: "/assets/roadmap.webp"
categories:
  - slae
  - infosec
tags:
  - Introduccion a Base de Datos
  - Comandos SQL
  - Dia 1
---

> Para crear una base de datos utilizamos el comando **CREATE DATABASE**

> Sintáxis:

```sql
CREATE DATABASE nombre;
```

Ejemplo practico 

```sql
CREATE DATABASE introdb;
```


---- 


> Para eliminar una base de datos utilizamos el comando **DROP DATABASE**

> Sintáxis:

```sql
DROP DATABASE nombre;
```

Ejemplo Practico

```sql
DROP DATABASE introdb;
```

---

> Para crear una tabla utilizamos el comando CREATE TABLE nombreDeLaTabla (Columna, Tipo-de-Dato, caracteristicas )

> Sintaxis:

```sql
CREATE TABLE personas 
					  (id tinyint unsigned auto_increment,
					  apellido varchar(255) ,
					  nombre varchar(255),
					  dni int unsigned ,
					  alta date
);
```

