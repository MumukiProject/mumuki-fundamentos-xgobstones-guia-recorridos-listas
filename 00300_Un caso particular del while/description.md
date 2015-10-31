Probablemente te estés preguntando _¿no habrá una forma más simple de recorrer una lista?_

Y la respuesta es que sí: se llama **repetición indexada**, aunque es más conocida como **sentencia foreach**, o simplemente `foreach`. 

Veamos cómo podrías haber implementado `sumatoria` usando `foreach`:

```puppet
function sumatoria(lista) {
    suma := 0

    foreach elemento in lista {
        suma := suma + elemento
    }

    return (suma)
}
```

> Siguiendo el ejemplo, intentá hacer `longitud` usando `foreach`.