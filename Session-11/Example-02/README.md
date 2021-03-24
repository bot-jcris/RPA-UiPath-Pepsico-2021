# Ejemplo 02: Enlazar a una base de datos

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Aprender a como conectarnos y desconectarnos de una base de datos.

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

2. Tener el controlador ODBC de SQLite instalado.

## 3. Desarrollo :hammer:

1. Crear el archivo ***EnlaceBaseDatos***.xaml (con el flujo de trabajo *Sequence*).

<div align="center">
<img src="assets/image01.png" align="center">
</div>
<br>

2. Añadir las actividades ***Connect*** y ***Disconnect***.

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Ir a las propiedades de la actividad ***Connect*** y escribir los siguientes valores:

    ConnectionString: ***`"Dsn=SQLite3 Datasource;Database=C:\UiPathCourse\Database\pepsico.db"`***

    ProviderName: ***`"dbcon_pepsico`***

    DatabaseConnection: ***`dbcon_pepsico`***

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Ir a las propiedades de la actividad ***Disconnect*** y escribir los siguientes valores:

    DatabaseConnection: ***`dbcon_pepsico`***

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Ejecutar el flujo y ver los resultados.

</div>