# Garbage collection

Garbage Collection es un proceso automático realizado por el motor de JavaScript que consiste en eliminar aquellos objetos que no tienen referencias o son inalcanzables para el contexto de ejecución, a través del algoritmo **mark-and-sweep** (marcado y barrido).

> (mark-and-sweep) hace referencia a cuando un tipo de dato se vuelve inalcanzable para el program

- Garbage Collection es importante para liberar espacio en memoria y no exista un desbordamiento en las tareas (stack overflow).
- Desde 2012, los navegadores utilizan un Garbage Collection y se ha actualizado continuamente.
- Cuando un objeto se queda ninguna referencia, se dice que el objeto es inalcanzable y entonces se libera el espacio en memoria.

> Cuando hay stack overflow en el navegador (chrome) las tareas se dejan de ejecutar para evitar su colapso, esto fue implementado en los últimos años.