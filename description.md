En esta guía vamos a ejercitar con **listas**, sin hacer uso del tablero. Si bien se espera que ya tengas una noción de listas, vamos a hacer un breve repaso para tener en cuenta en los próximos ejercicios.

Lo que sabemos hasta ahora de una lista es que una lista es una colección...
* ...**ordenada**: no da lo mismo la lista `[1, 2, 3]` que la lista `[3, 2, 1]` o `[2, 1, 3]`.
* ...de **valores**: que pueden ser números, colores, direcciones, registros... ¡e incluso otras listas!
* ...de un **mismo tipo**: no vale mezclar; cosas como `[1, Azul]` o `[Negro, Verde, Oeste]` no son listas.
* ...**inmutable**: es decir, que no puede cambiar luego de ser creada.

Contamos además con algunas funciones que nos sirven para **manipular** dichas listas:
* `isEmpty(lista)`: nos dice si la lista está vacía.
* `head(lista)`: dada una lista **con elementos**, nos devuelve el primer elemento.
* `tail(lista)`: dada una lista **con elementos**, nos devuelve todos los elementos menos el primero.
* `last(lista)`: dada una lista **con elementos**, nos devuelve el último elemento.
* `init(lista)`: dada una lista **con elementos**, nos devuelve todos los elementos menos el último.

Teniendo esto en mente, ya estamos listos para avanzar al primer ejercicio: ¡vamos!