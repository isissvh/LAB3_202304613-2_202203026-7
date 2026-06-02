# Laboratorio 2: Arquitectura y Organización de Computadores

## 1. Integrantes
* **Nombre:** Isidora Villegas | **Rol:** 202203026-7
* **Nombre:** Héctor Chanampe | **Rol:** 202304613-2
* **Paralelo:** 201


---

## Contexto  
Readme de la tarea 3 de la asignatura de arquitectura y organización de computadores. Aquí encontrará información importante sobre como se desarrolló la tarea hasta como poder utilizar el programa.

## Desarrollo

1. Para un mejor orden se creó primero un diagrama con todos los posibles valores del display
2. Luego se crearon tanto la tabla de verdad como los Mapas de Karnaugh incluyendo D0, D1, D2, D3.
3. Se procedió a las simplificaciones de cada expresión obtenida
4. Con aquellos resultados se crearon los circuítos con la herramienta 'logisim-evolution'
   - Dentro del circuito se crearon 'main' (principal para el funcionamiento), los subcircuitos 'A', ... 'G', el decodificador, EstadoActual (estadoguardado), Estado Siguiente (estadosig) y detectorF.
5. Se comprobaron todos los mensajes y su funcionamiento óptimo

## Instrucciones para ejecutar el circuito

1. Cargue el archivo main.circ en el software.
2. Asegúrese de estar posicionado en el circuito llamado "main".
3. Seleccione la herramienta Poke (icono de la mano en la barra superior).
4. Interactúe con el MUX inicial y el Reloj para avanzar por los nodos hasta llegar a F.
5. El display de 7 segmentos mostrará automáticamente el símbolo decodificado correspondiente al suceso pedido.
