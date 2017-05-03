Lo primero que nos va a interesar de una lista es aprender a **recorrerla**, y para eso vamos a hacer algo muy parecido a lo que ya veníamos trabajando para los tableros. 

Veamos, por ejemplo, el código necesario para contar la cantidad de elementos de una lista:

```gobstones
function longitud(lista) {
    recorrido := lista
    cantidad := 0

    while (not isEmpty(recorrido)) {
        cantidad := cantidad + 1
        recorrido := tail(recorrido)
    }

    return (cantidad)
}
```

> Copiá el código que te proponemos en el editor y mirá cómo calcula la longitud de algunas listas.