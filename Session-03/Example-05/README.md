# Ejemplo 05: Copiar y mover un archivo

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Aprender a cómo copiar y mover un archivo
- Aprender a utilizar las actividades *Copy File* y *Move File*.
- Entender la propiedad *Overwrite*.

## 2. Desarrollo :hammer:

1. Crear manualmente las carpetas con nombre **"B"** y **"C"** en el directorio "C:\UiPathCourse\\".

<div align="center">

<img src="assets/image01.png" align="center">

</div>

<br>

2. Dentro de la carpeta "A", solo deberá existir el archivo "test.txt".

<div align="center">

<img src="assets/image02.png" align="center">

</div>

<br>

3. Crear el archivo ***CopiarMoverArchivo.xaml*** (con el flujo de trabajo *Flowchart*) y añadir la actividad **Copy File**.

<div align="center">

<img src="assets/image03.png" align="center">

</div>

<br>

4. Dentro de la actividad *Copy File* ingresar los siguientes valores:

- From: **`"C:\UiPathCourse\A\test.txt"`**
- To: **`"C:\UiPathCourse\B\test.txt"`**

    **NOTA:** Seleccionar la opción *Overwrite*.

<div align="center">

<img src="assets/image04.png" align="center">

</div>

<br>

5. Añadir la actividad **Move File**, tal y como se muestra en la imagen:

<div align="center">

<img src="assets/image05.png" align="center">

</div>

<br>

6. Dentro de la actividad *Move File* ingresar los siguientes valores:

- From: **`"C:\UiPathCourse\B\test.txt"`**
- To: **`"C:\UiPathCourse\C\test.txt"`**

    **NOTA:** Seleccionar la opción *Overwrite*.

<div align="center">

<img src="assets/image06.png" align="center">

</div>

<br>

7. Ejecutar el flujo y revisar los resultados.

<br>

</div>