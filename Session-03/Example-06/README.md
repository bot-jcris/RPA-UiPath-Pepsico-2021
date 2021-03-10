# Ejemplo 06: Eliminar un archivo y una carpeta

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Aprender a cómo eliminar un archivo y una carpeta
- Aprender a utilizar la actividad *Delete*.

## 2. Desarrollo :hammer:

1. Verificar que en el directorio "C:\UiPathCourse\\" tengas dos carpetas: **B** y **C**. Que la carpeta B este vacía y la carpeta C tengo solamente el archivo "test.txt".

2. Crear el archivo ***EliminarArchivoCarpeta.xaml*** (con el flujo de trabajo *Flowchart*) 

3. Buscar y añadir la actividad **Delete**, tal y como se muestra en la imagen:

<div align="center">

<img src="assets/image03.png" align="center">

</div>

<br>

4. Dar doble clic a la actividad *Delete* y escribir lo siguiente: **`"C:\UiPathCourse\B"`**

<div align="center">

<img src="assets/image04.png" align="center">

</div>

<br>

5. Añadir una segunda actividad *Delete*.

<div align="center">

<img src="assets/image05.png" align="center">

</div>

<br>

6. Dar doble clic a la segunda actividad *Delete* y escribir lo siguiente: **`"C:\UiPathCourse\C\test.txt"`**

<div align="center">

<img src="assets/image06.png" align="center">

</div>

<br>

7. Ejecutar el flujo y revisar los resultados.

<br>

</div>