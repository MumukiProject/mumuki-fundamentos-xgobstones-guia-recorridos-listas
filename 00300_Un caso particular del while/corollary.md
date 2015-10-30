Formalicemos algunas cuestiones sobre el `foreach`:

* La sintaxis es `foreach variable in lista { }`, donde `variable` puede ser cualquier nombre que empiece en minúscula, y `lista` tiene que ser una lista.
* Repite todos los comandos que estén entre llaves tantas veces como elementos tenga la lista, guardando en `variable` el elemento que está recorriendo cada vez.
* Es muy útil cuando queremos recorrer una lista **por completo** y **de izquierda a derecha**. Para otros casos seguiremos usando el `while`.