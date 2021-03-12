# Ejemplo 03: Recorrer los registros de un DataTable

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Entender...

## 2. Desarrollo :hammer:

1. Ir al panel de ***Project***, localizar el archivo que realizaste en el ejemplo 02: **AgregarQuitarFilasDataTable**.xaml y seleccionarlo. Realizar las combinaciones de teclas: ***Ctrl + C*** y ***Ctrl + V***. Aparecerá un archivo con el siguiente nombre: **AgregarQuitarFilasDataTable - Copy (1)**.

<div align="center">
<img src="assets/image01.png" align="center">
</div>
<br>

2. Dar clic derecho al archivo copiado y seleccionar la opción ***Rename***.

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Cambiar el nombre a: **`RecorrerRegistrosDataTable`** y seleccionar la opción *OK*.

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Dar doble clic al archivo **RecorrerRegistrosDataTable**.

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Eliminar las actividades ***Output Data Table*** y ***Write Line***.

6. Seleccionar la actividad principal: **AgregarQuitarFilasDataTable**.

<div align="center">
<img src="assets/image06.png" align="center">
</div>
<br>

7. Ir al panel de ***Properties*** y en la propiedad ***DisplayName*** y escribir **`Actividad Principal`**

<div align="center">
<img src="assets/image07.png" align="center">
</div>
<br>

8. Añadir la actividad ***For Each Row in Data Table***.

<div align="center">
<img src="assets/image08.png" align="center">
</div>
<br>

9. Cambiar los valores de la actividad por los siguientes:

    - For each: **`fila`**
    - In: **`dtb_primerDatatable`**

<div align="center">
<img src="assets/image09.png" align="center">
</div>
<br>

10. Añadir la actividad ***Message Box*** dentro del ***Body*** del ***For Each Row in Data Table*** y escribir el mensaje: **`fila(0).ToString+" : "+fila(1).ToString`**

<div align="center">
<img src="assets/image10.png" align="center">
</div>
<br>


2. Ejecutar el flujo y ver los resultados.

</div>