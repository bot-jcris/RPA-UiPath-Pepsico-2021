# Ejemplo 02: Leer rango y pegar en nueva hoja de Excel

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Repasar el funcionamiento de la actividad *Read Range* y *Write Range*.
- Conocer como leer todo el contenido de una hoja.

## 2. Requisitos :gear:

**NOTA: Realizar el procedimiento ejercicio o el procedimiento manual.**

### Procedimiento ejercicio

1. Realizar el ejemplo 01 (Escribir un DataTable en un Excel).

### Procedimiento manual

1. Verificar que la carpeta **Excel** este creada en la carpeta **C:\UiPathCourse**. Si no existe crearla.

2. Dentro de la carpeta **C:\UiPathCourse\Excel** verificar que **exista** el archivo Excel con nombre: **ListaCompras.xlsx**. Si no existe crear el archivo.

3. Verificar que el archivo Excel con nombre **ListaCompras.xlsx** tenga solo la pestaña con nombre **`"Sheet1"`**

<div align="center">
<img src="assets/image0.03.png" align="center">
</div>
<br>

4. Verificar que el contenido del Excel con nombre **ListaCompras.xlsx** sea como se muestra en la imagen:

<div align="center">
<img src="assets/image0.04.png" align="center">
</div>
<br>

## 3. Desarrollo :hammer:

1. Crear el archivo ***LeerRangoEscribirNuevaHojaExcel***.xaml (con el flujo de trabajo *Sequence*).

2. Añadir la actividad ***Excel Application Scope*** y escribir la ruta del archivo: **`"C:\UiPathCourse\Excel\ListaCompras.xlsx"`**

3. Añadir la actividad ***Read Range*** dentro del ***Do*** de la actividad ***Excel Application Scope***. 

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Ir a las propiedades de la actividad ***Read Range*** y escribir los siguientes valores:

    - *Input / Range*: **`""`**
    - *Input / SheetName*: **`"Sheet1"`**
    - *Options / AddHeaders*: **Habilitar**
    - *Output / DataTable*: **`dtb_listaCompras`** (**TIP:** Crear y utilizar la variable mediante **Ctrl + K**)

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Añadir la actividad ***Write Range***.

<div align="center">
<img src="assets/image05.png" align="center">
</div>
<br>

6. Ir a las propiedades de la actividad ***Write Range*** y escribir los siguientes valores:

    - Destination / SheetName: **`"Sheet2"`**
    - Destination / StartingCell: **`"B2"`**
    - Input / DataTable: **`dtb_listaCompras`**
    - Options / AddHeaders: **`Habilitar`**

<div align="center">
<img src="assets/image06.png" align="center">
</div>
<br>

7. Ejecutar el flujo y ver los resultados.

</div>