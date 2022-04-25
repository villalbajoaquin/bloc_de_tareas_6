# bloc_de_tareas_6
App de consola de JavaScript con Node.js sobre una lista de tareas.

# Funciones principales:
## Listar tareas:
Al ejecutar en la consola `node app listar` se deberán listar todas las tareas existentes con título y estado.

## Crear una nueva tarea:
Al ejecutar en la consola `node app crear 'título de tarea'` la nueva tarea se guardará en la lista de tareas actuales, el **título**
vendrá del argumento ingresado por consola y el **estado** de la tarea será siempre **'pendiente'**.

## Filtrar tareas por estado:
Al ejecutar en la consola `node app filtrar 'estado de tarea'`, la consola nos mostrará una lista nueva con las tareas ya filtradas con
el mismo estado que pasamos como **argumento**.

## Manejo de Errores:
- Si no pasamos ningun argumento en la consola al ejecutarla (ej: `node app`), la consola nos devuelve el mensaje: **'Atención - Tienes que pasar una acción'**
- En cambio, si al ejecutar nuestra app en la consola, como argumento no pasamos las palabras claves de las funciones (listar - crear - filtrar)(ej: `node app a`),
la consola nos devuelve el mensaje: **'No entiendo qué quieres hacer'**.

## Objetivos:
Esta app es un ejercicio para poner práctica el manejo de módulos, los metodos de arrays, la declaración `switch`, entre otros.
