# Ejemplo 01: Ciclo infinito

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Entender el funcionamiento de la estructura *While*.
- Construir el siguiente flujo:

<div align="center">

<img src="assets/image0.png" align="center" width="30%">

</div>

<br>

## 2. Desarrollo :hammer:

1. Crear el archivo ***CicloInfinito.xaml*** (con el flujo de trabajo *Flowchart*).

2. Crear una variable con las siguientes características:

    - Name: **`bln_respuesta`**
    - Variable type: **`Boolean`**

<div align="center">

<img src="assets/image02.png" align="center">

</div>

<br>

3. Añadir la actividad ***Assign***, hacer la conexión como se muestra en la imagen y escribir los siguientes datos:

    - Del lado izquierdo: **`bln_condicion`**
    - Del lado derecho: **`True`**

<div align="center">

<img src="assets/image03.png" align="center">

</div>

<br>

4. Añadir la actividad ***While*** y hacer la conexión como se muestra en la imagen:

<div align="center">

<img src="assets/image04.png" align="center">

</div>

<br>

5. Dar doble clic en la actividad *While* y escribir dentro de la sección *Condition*: *`bln_condition`*

<div align="center">

<img src="assets/image05.png" align="center">

</div>

<br>

6. Añadir la actividad ***Write Line*** dentro del ***Body*** de la actividad *While*, tal como se muestra en la imagen y escribir en su interior: *`DateTime.Now.ToString`*

<div align="center">

<img src="assets/image06.png" align="center">

</div>

<br>

7. Ejecutar el flujo y ver los resultados.

</div>