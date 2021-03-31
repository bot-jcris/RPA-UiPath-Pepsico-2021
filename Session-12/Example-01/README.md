# Ejemplo 01: Enviar correo

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer...

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

## 3. Desarrollo :hammer:

1. Crear el archivo ***EnviarCorreo***.xaml (con el flujo de trabajo *Sequence*).

2. Añadir la actividad ***Send Outlook Mail Message***

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

3. Ir a las propiedades de la actividad ***Send Outlook Mail Message*** y modificar las siguientes variables:

    - *Email > Body:* **`Este es un contenido de prueba`**
    - *Email > Subject:* **`Prueba`**
    - *Receiver > To:* **TuCorreoInstitucional@pepsico.com**

<div align="center">
<img src="assets/image03.png" align="center">
</div>
<br>

4. Ejecutar el flujo y revisar tu bandeja de entrada de correo.

<div align="center">
<img src="assets/image04.png" align="center">
</div>
<br>

</div>