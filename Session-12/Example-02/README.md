# Ejemplo 02: Enviar Correo HTML

<div style="text-align: justify;">

## 1. Objetivos :dart:

- Conocer el Try Catch

## 2. Requisitos :gear:

1. Tener instalado UiPath Studio.

## 3. Desarrollo :hammer:

1. Crear el archivo ***EnviarCorreoHTML***.xaml (con el flujo de trabajo *Sequence*)

2. Añadir la actividad ***Open Browser*** y escribir: **`"www.facebook.com"`**

<div align="center">
<img src="assets/image02.png" align="center">
</div>
<br>

```HTML
"<!DOCTYPE html><html><head/><body><div><font size='4' face='Arial Narrow' color='black'>Hola, </font><font size='4' face='Arial Narrow' color='#65349d'></font><p><font size='4' face='Arial Narrow' color='black'>Para informarte que el proceso fue realizado satisfactoriamente</font></p></div><br><div><p><font size='4' face='Arial Narrow' color='black'>Saludos,</font></p></div><div><table width='60%' align='left'><tr><td width='55%'><table width='100%' cellpadding='2'><tr><td><b><font size='4' face='Arial Narrow' color='#65349d'>"+str_nombre.ToUpper+"</font></b></td></tr><tr><td><font size='4' face='Arial Narrow' color='black'>Experto en RPA</font></td></tr><tr><td><font size='4' face='Arial Narrow' color='black'>https://www.pepsico.com.mx/</font></td></tr></table></td></tr></table></div></body></html>"
```



</div>