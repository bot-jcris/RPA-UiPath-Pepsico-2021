# Ejemplo 03: Mostrar cada de una lista de compras

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Entender el funcionamiento de la estructura *For Each*.
- Conocer la variable *Array*.

## 2. Desarrollo :hammer:

1. Crear el archivo ***MostrarListaCompras*** (con el flujo de trabajo *Flowchart*).

2. Crear la variable ***`arr_listaCompras`***, desplegar la lista de opciones de la sección *Variable Type* y escoger la opción *Browse for types*.

<div align="center">

<img src="assets/image02.png" align="center">

</div>

<br>

3. Escribir en la sección *Type Name*: ***`System. Array`***
    
    Seleccionar la opción que aparece en la ruta **mscorlib / System**. Y dar clic en *OK*.

<div align="center">

<img src="assets/image03.png" align="center">

</div>

<br>

4. Añadir la actividad ***For Each***, tal como se muestra a continuación:

<div align="center">

<img src="assets/image04.png" align="center">

</div>

<br>

5. Seleccionar la actividad *For Each*, ir al panel de *Properties* y verificar que la propiedad ***TypeArgument*** tenga la opción ***String***.

<div align="center">

<img src="assets/image05.png" align="center">

</div>

<br>

6. Escribir los siguientes valores:
    - *ForEach* ***`bebida`*** *In* ***`arr_listaCompras`***

    Dentro del *Body*, añadir la actividad *MessageBox* y escribir: ***`bebida`***

<div align="center">

<img src="assets/image06.png" align="center">

</div>

<br>

7. Ejecutar el flujo y ver los resultados.

</div>