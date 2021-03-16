# Ejemplo 01: Utilizar un archivo excel

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer la actividad *Excel Application Scope*.
- Comprender el uso de la propiedad *Create if not exists*. 

## 2. Desarrollo :hammer:

1. Crear manualmente la carpeta **Excel** en la carpeta **C:\UiPathCourse**.

2. Dentro de la carpeta **C:\UiPathCourse\Excel** crear manualmente un nuevo documento de Excel con el nombre: **Nuevo.xlsx**.

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Crear el archivo ***UtilizarExcel.xaml*** (con el flujo de trabajo *Sequence*).

4. Añadir la actividad ***Excel Application Scope*** y escribe la ruta **`C:\UiPathCourse\Excel\Nuevo.xlsx`**

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

5. Añade la actividad ***Message Box*** dentro del ***Do*** del ***Excel Application Scope***. Escribir en el ***Message Box***: **`"esperar"`**

<div align="center">
<img src="assets/image05.png" align="center">
</div>
<br>

6. Ejecutar el flujo y ver los resultados.

7. Ir al panel de *Properties* de la actividad ***Excel Application Scope*** y desmarcar la opción ***Create if not exits***.

<div align="center">
<img src="assets/image07.png" align="center">
</div>
<br>

8. Ejecutar el flujo y ver los resultados.

9. En la actividad ***Excel Application Scope*** añadida, cambiar el nombre del archivo a utilizar: **`C:\UiPathCourse\Excel\Nuevo2.xlsx`** 

<div align="center">
<img src="assets/image09.png" align="center">
</div>
<br>

10. Ejecutar el flujo y ver los resultados.

</div>