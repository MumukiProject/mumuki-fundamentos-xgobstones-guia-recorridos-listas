Te dejamos la versión de `longitud` usando `while`, identificá qué partes se ocupan del recorrido y eliminalas, ya que de eso se encarga el `foreach`.

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