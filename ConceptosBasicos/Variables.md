# Conceptos Básicos

## Variables

Una variable es un espacio reservado en memoria para almacenar valores
La shell nos permite definir variables donde podemos guardar datos.

Es como una cajita donde puedes guardar cosas, como números o palabras.
Tenemos dos zonas donde las podemos almacenar, la área local y la de entorno.

- **Variables locales:** Solo son visibles para la Shell donde estamos trabajando, no son visibles por cualquier otro subshell.
- **Variables de entorno**: Son visibles para la Shell donde estamos trabajando y para cualquier otro subshell


> **En resumen:** Una variable es un espacio reservado en memoria para almacenar valores.
> Las variables locales son visibles solo dentro de la shell donde se definen, mientras que las variables de entorno son visibles para cualquier subshell.

| Comandos                         | Acción |
| -----------                      |-------------|
| **set**                          | Ver todas las variables definidas |
| **env**                          | Ver todas las variables de entorno definidas |
| **nombre_var=valor_var**         | Definir variable y asignarle valor |
| **export nombre_var=valor_var**  | Definir variable de entorno y asignarle un valor |
| **export nombre_var**            | Convertir variable local a variable de entorno |
| **unset nombre_var**             | Eliminar una variable |
