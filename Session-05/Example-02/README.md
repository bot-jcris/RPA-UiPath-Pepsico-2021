# Ejemplo 02: 

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Entender...

## 2. Desarrollo :hammer:

1. Crear el archivo ***`AgregarQuitarFilasDataTable`***.xaml (con el flujo de trabajo *Sequence*).

2. Crear una variable con las siguientes características:

    - Name: **`dtb_primerDatatable`**
    - Variable type: **`Datatable`**

    **Tip:** Si no te aparece el tipo de variable *DateTable*, dentro del buscador escribe *System.Data.DataTable*

3. Regresar al documento **PrimerDatatable**. Dar clic derecho a la actividad ***Build Data Table*** y seleccionar el botón ***Copy***.

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Regresar al documento **AgregarQuitarFilasDataTable**. Dar clic derecho a la actividad *AgregarQuitarFilasDateTable* y seleccionar la opción ***Paste***.

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Añadir la actividad ***Remove Data Row***.

<div align="center">
<img src="assets/image05.png" align="center">
</div>
<br>

6. Ir a las propiedades de la actividad ***Remove Data Row*** y escribir los siguientes valores:

    - Input / Datatable: **`dtb_primerDatatable`**
    - Input / RowIndex: **`1`**

<div align="center">
<img src="assets/image06.png" align="center">
</div>
<br>

7. Añadir la actividad ***Add Data Row***.

<div align="center">
<img src="assets/image07.png" align="center">
</div>
<br>

8. Ir a las propiedades de la actividad ***Add Data Row** y escribir los siguientes valores:

    - Input / ArrayRow: **`{"dato3",3}`**
    - Input / DataTable: **`dtb_primerDatatable`**

<div align="center">
<img src="assets/image08.png" align="center">
</div>
<br>

9. Añadir la actividad *Output Date Table*.

<div align="center">
<img src="assets/image09.png" align="center">
</div>
<br>

10. Ir a las propiedades de la actividad *Output Data Table* y escribir los siguientes valores:

    - Input / Datatable: **`dtb_primerDatable`**
    - Output / Text: **`str_primerDatatable`** ( **TIP:** Utilizar *Ctrl + K* )

<div align="center">
<img src="assets/image10.png" align="center">
</div>
<br>

11. Añadir la actividad *Write Line* y dentro de su campo de texto escribir **`str_primerDatatable`**

<div align="center">
<img src="assets/image11.png" align="center">
</div>
<br>

12. Ejecutar el flujo y ver los resultados.

</div>