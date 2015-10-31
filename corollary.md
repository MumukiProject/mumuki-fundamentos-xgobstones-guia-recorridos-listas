A lo largo de estos ejercicios aprendimos a recorrer listas con distintos objetivos:

* **plegar** una lista, calculando un único valor a partir de procesar cada elemento (en inglés a esto se lo conoce como **fold**)
* **mapear** una lista a otra, ejecutando una transformación sobre cada elemento
* **transformar** una lista en otra, de alguna forma arbitraria
* **filtrar** una lista, reduciéndola a los elementos que nos interesan según algún criterio
* **buscar** un elemento dentro de una lista, siguiendo algún criterio

Vimos también que existen dos formas de recorrer una lista:

* usando `foreach`: que tiene la ventaja de que recorre la lista por nosotros y expresa mejor la intención, y la desventaja de que no siempre podemos usarlo (porque es un caso particular del `while`)
* usando `while`: que tiene la ventaja de ser más poderoso porque tenemos el control, y la desventaja de que hay que hacer todo _a mano_ y por lo tanto tenemos más posibilidad de equivocarnos
