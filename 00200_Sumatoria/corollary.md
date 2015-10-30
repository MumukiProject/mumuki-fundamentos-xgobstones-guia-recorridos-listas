¡Bien! 

Fijate que el **esquema de recorrido** es el mismo que usaste para la función anterior, sólo cambian 2 cosas:

* el **valor inicial** de la variable o **caso base**, que por ahora viene siendo `0` pero podría ser cualquier otro
* cómo **procesamos cada elemento de la lista** y modificamos ese valor

Podría generalizarse en algo así (los comentarios deberían reemplazarse por código):

```puppet
function hacerAlgunCalculoSobreUnaLista(lista) {
    recorrido := lista
    // resultado := "algun valor interesante"

    while (not isEmpty(recorrido)) {
        // resultado := "algun cómputo, que puede usar al head(recorrido) o no"
        recorrido := tail(recorrido)
    }

    return (resultado)
}
```