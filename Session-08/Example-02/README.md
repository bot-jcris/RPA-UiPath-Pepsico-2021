# Ejemplo 02: Buscar en la página web Google

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer las actividades *Type Into* y *Click*

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

## 3. Desarrollo :hammer:

1. Crear el archivo ***BuscarPaginaWebGoogle***.xaml (con el flujo de trabajo *Sequence*).

2. Añadir la actividad ***Open Browser***.

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Escribir la siguiente URL: **`"www.google.com"`**

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Añadir la actividad ***Type Into*** y dar clic en la opción ***Indicate element inside Browser***.

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Posicionar el cursor encima de la caja de texto del buscador de la página web y dar clic.

<div align="center">
<img src="assets/image05.png" align="center">
</div>
<br>

6. Escribir en la actividad ***Type Into***: **`"Google Gravity"`**

<div align="center">
<img src="assets/image06.png" align="center">
</div>
<br>

7. Añadir la actividad ***Click*** y dar clic en la opción ***Indicate element inside Browser***.

<div align="center">
<img src="assets/image07.png" align="center">
</div>
<br>

8. Posicionar el cursor encima del botón **Buscar con Google** y dar clic.

<div align="center">
<img src="assets/image08.png" align="center">
</div>
<br>

9. Añadir la actividad ***Click*** y dar clic en la opción ***Indicate element inside Browser***.

<div align="center">
<img src="assets/image09.png" align="center">
</div>
<br>

10. Posicionar el cursor encima de la primera opción que aparece de la búsqueda y dar clic.

<div align="center">
<img src="assets/image10.png" align="center">
</div>
<br>

11. Ejecutar el flujo y ver los resultados.

</div>