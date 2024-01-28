# JSON [^1]
JSON (acrónimo de JavaScript Object Notation, 'notación de objeto de JavaScript') es un formato de texto sencillo para el intercambio de datos. 
Se trata de un subconjunto de la notación literal de objetos de JavaScript, aunque, debido a su amplia adopción como alternativa a XML, se considera un formato independiente del lenguaje.

## Historia [^2]
JSON fue creado a principios de la década de 2000 por Douglas Crockford como una forma de mejorar los formatos de almacenamiento de datos existentes, como XML y CSV. 
Fue diseñado para ser más legible que otros formatos, facilitando a los desarrolladores la lectura y escritura de datos. 
La sintaxis de JSON se basa en JavaScript, lo que facilita aún más a los desarrolladores web utilizando su lenguaje de programación favorito. 
Hoy en día, JSON es uno de los formatos de almacenamiento de datos más populares que se utilizan en una amplia variedad de aplicaciones de software.

## Caracteristicas
:heavy_check_mark: Uno de los lenguajes más secillos para hacer un Parseador.

:heavy_check_mark: En Java se puede usar [`eval()`](https://es.wikipedia.org/wiki/Eval) para analizarlo.

:heavy_check_mark: Empleado en entornos donde el tamñao del flujo de datos entre cliente y servidor es de vital importacia.

## Ejemplos
```
{
    "menu": {
        "id": "file",
        "value": "File",
        "popup": {
            "menuitems": [
                {
                    "value": "New", "onclick": "CreateNewDoc()"
                },{
                    "value": "Open", "onclick": "OpenDoc()"
                },{
                    "value": "Close", "onclick": "CloseDoc()"
                }
            ]
        }
    }
}
```

### Accesos

[JSONvsYAML](./JSONvsYAML.md)

[Home](/Readme.md)

### Referecias

[^1]:https://es.wikipedia.org/wiki/JSON
[^2]:https://www.arimetrics.com/glosario-digital/json#Origen_de_JSON
