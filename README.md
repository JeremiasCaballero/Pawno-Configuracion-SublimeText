# Pawno-Configuracion-SublimeText
## Descarga 🚀

Puede descargar sublime text en su ultima version en el siguiente [Link](https://www.sublimetext.com/)


## Configuracion ⚙️

* Abrir sublime text 3 ir Preferences-Package Control - Escribir package install y presionar enter.
* Buscar pawn sintaxis y instalar

Ahora podra notar el resaltado de sintaxs de pawno (basado en C).

## Agregando el compilador de pawno ⚙️
Para poder compilar necesita indicarle a sublime text que compilador usara.

* Ir a tools-build System - new build System.
* Copiar el siguiente json con su directorio donde se encuentra el compilador pawno (pawnocc.exe) (por defecto raizProyecto/pawno)



```
{
 "cmd": ["pawncc.exe", "-i includes", "$file", "-;+"],
 "path": "rutaProyecto/pawno"
}

```
Guardar y asegurarse que la extension del archivo con la que se guardo sea .sublime-build

importante !

Si copia y pega la direcion directamente es posible que quede por ejemplo: rutaProyecto\pawno Reemplazar \ por / ya que se intrepetra como caracter



