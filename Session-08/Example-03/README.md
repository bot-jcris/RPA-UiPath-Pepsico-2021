# Ejemplo 03: Tomar pantallazo de página web Wikipedia

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer las actividades *Take Screenshot* y *Save Image*.

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

2. Crear manualmente la carpeta **Web** dentro de la ruta **"C:\UiPathCourse"**.

## 3. Desarrollo :hammer:

1. Crear el archivo ***TomarPantallazoPaginaWeb***.xaml (con el flujo de trabajo *Sequence*).

2. Añadir la actividad ***Open Browser***.

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Escribir la siguiente URL: **`"www.wikipedia.com"`**

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Añadir la actividad ***Take Screenshot*** y seleccionar la opción ***Indicate element inside browser***.

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Posicionar el curso encima de la página web y dar clic.

<div align="center">
<img src="assets/image05.png" align="center">
</div>
<br>

6. Ir a las propiedades de la actividad ***Take Screenshot*** y escribir los siguientes valores:

    - *Output / Screenshot*: **scrsh_portadaWikipedia** (**TIP:** Crear y utilizar mediante *Ctrl + K*)

<div align="center">
<img src="assets/image06.png" align="center">
</div>
<br>

7. Añadir la actividad ***Save Image***.

<div align="center">
<img src="assets/image07.png" align="center">
</div>
<br>

8. En la actividad ***Save Image*** escribir los siguientes valores:

    - *Image*: **`scrsh_portadaWikipedia`**
    - *File Path*: **`"C:\UiPathCourse\Web\PortadaWikipedia.jpg"`**

<div align="center">
<img src="assets/image08.png" align="center">
</div>
<br>


11. Ejecutar el flujo y ver los resultados.

</div>