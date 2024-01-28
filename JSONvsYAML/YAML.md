# YAML [^1]
YAML es un formato de serialización de datos legible por humanos inspirado en lenguajes como XML, C, Python, Perl, así como en el formato de los correos electrónicos (RFC 2822). 

## Historia [^2]
YAML fue propuesto por Clark Evans en 2001, quien lo diseñó junto a Oren Ben-Kiki. YAML es un acrónimo recursivo que significa "YAML Ain't Another Markup Language (en castellano, "YAML no es otro lenguaje de marcado"). 
A comienzos de su desarrollo, YAML significaba "Yet Another Markup Language" ("Otro lenguaje de marcado más") para distinguir su propósito centrado en los datos en lugar del marcado de documentos. 
Sin embargo, dado que se usa frecuentemente XML para serializar datos y XML es un auténtico lenguaje de marcado de documentos, es razonable considerar YAML como un lenguaje de marcado ligero. 
El formato se lleva utilizando desde 2001 y existen utilidades para procesar YAML en una gran variedad de lenguajes de programación.

## Caracteristicas
:heavy_check_mark: Todos los datos son representables como listas, mapeos y datos escalares

:heavy_check_mark: Sintaxis sencilla y diseñada para que fuera muy legible y mapeable simultaneamente.

:heavy_check_mark: Gasta una notación basica de sangria y/o un conjunto de carateres Sigil distintos de XML.

## Ejemplos
```
 --- # Películas favoritas, formato de bloque
 - BotijoAzul
 - BotijoVerde
 - Viridiana
 - Psicosis
 ...
 --- # Lista de la compra, formato en línea
 [leche, pan, huevos]
 [chorizo, morcilla, botijo, pollo]
```

### Accesos

[JSON vs YAML](./JSONvsYAML.md)

[Home](/Readme.md)

### Referecias

[^1]:https://es.wikipedia.org/wiki/YAML
[^2]:https://www.ecured.cu/YAML#Origen
