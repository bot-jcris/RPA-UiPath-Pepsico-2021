# Ejemplo 01: Automatizando Facebook

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer .................

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

## 3. Desarrollo :hammer:

1. Crear el archivo ***FacebookLogin***.xaml (con el flujo de trabajo *Sequence*).

2. Añadir la actividad ***Open Browser*** y escribir: **`"www.facebook.com"`**

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Ir a las propiedades de la actividad ***Open Browser*** y escribir lo siguiente: 

    - *Input > BrowserType*: **BrowserType.Chrome**

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Cerrar los navegadores web **Chrome**

5. Modificar el contenido de la actividad ***Open Browser*** y escribir: **`www.facebook.com`**

7. Ejecutar el flujo y ver los resultados.

8. Modificar el contenido de la actividad ***Open Browser*** y escribir: **`www.google.com`**. Seleccionar el botón que se indica en la siguiente imagen:

<div align="center">
<img src="assets/image08.png" align="center">
</div>
<br>

9. Añadir la actividad ***Click*** y seleccionar la opción ***Indicate element inside browser***.

<div align="center">
<img src="assets/image09.png" align="center">
</div>
<br>

10. Posicionar el cursor sobre el botón **Me siento con suerte** y dar clic.

<div align="center">
<img src="assets/image10.png" align="center">
</div>
<br>

11. Cerrar los navegadores web **Chrome**

12. Ejecutar el flujo y ver los resultados.

13. Cerrar los navegadores web **Chrome**

14. Modificar el contenido de la actividad ***Open Browser*** y escribir: **`www.facebook.com`**

<div align="center">
<img src="assets/image14.png" align="center">
</div>
<br>

15. Ir a las propiedades de la actividad ***Click*** y escribir lo siguiente:

    - *Input > Target > Timeout (miliseconds):* **`5000`**

<div align="center">
<img src="assets/image15.png" align="center">
</div>
<br>

16. Añadir la actividad ***Message Box*** y escribir: **`"CONTINUA"`**

<div align="center">
<img src="assets/image16.png" align="center">
</div>
<br>

17. Ejecutar el flujo y ver los resultados.

<div align="center">
<img src="assets/image17.png" align="center">
</div>
<br>


</div>