Bastante parecido, ¿no? Analicemos línea por línea lo que acabás de hacer:

* `recorrido := lista`: como dijimos, las listas son **inmutables**. Entonces para avanzar en el recorrido tenemos que crear una nueva lista, con menos elementos que la anterior y necesitamos una variable para guardar ese progreso.
* `cantidad := 0`: nuestro objetivo es contar cuántos elementos hay, así que en principio esa cantidad es 0.
* `while (not isEmpty(recorrido))`: en español sería "mientras la lista de recorrido no sea vacía", o, siendo un poco más relajados, "mientras me queden elementos por recorrer"
* `cantidad := cantidad + 1`: suma 1 a la cantidad, porque ya pasamos por otro elemento más.
* `recorrido := tail(recorrido)`: esto es quizás lo más importante de todo, ya que sin esta línea el programa no terminaría nunca. Lo que estamos haciendo es descartar el primer elemento (porque ya lo procesamos) y quedándonos con lo que todavía nos falta (el resto de la lista, la cola).