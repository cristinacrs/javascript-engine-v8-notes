## Global Enviroment

1. global Object == window
2. global object == this == window
3. Outer enviroment

## Execution Context

Corre el código en un stack de tareas, la última tarea en añadirse será la primera en ejectutarse (LIFO)

Una vez que el motor de JavaScript está interactuando con el navegador, realiza los siguientes procesos:

1. **Parser:** genera un parseo del documento completo mediante palabras claves.
2. **Abstract Syntax Tree:** Se crea a partir de los nodos que genera el parser. Es una estructura de árbol que representa tu código sintácticamente.
3. **Interpreter:** El intérprete recorre el AST y genera Bytecode basado en la información que contiene.Si el intérprete reconoce que el código se puede optimizar no genera bytecode genera *profile y complier* para realizar un proceso de optimización.
   >Bytecode: es un lenguaje no binario que interpreta la computadora
4. **Profiler y compiler:** El profiler monitorea el código para optimizarlo, después lo compila y lo regresa como bytecode. En este paso también se encuentran errores de programación como el hoisting.


