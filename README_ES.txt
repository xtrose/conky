xtrose Media Studio
Autor: Moses Rivera
Web: https://xtrose.com
Correo: media.studio@xtrose.com



Construye tu propia barra lateral de Conky con xtrose Conky.
xtrose Conky puede manejar múltiples resoluciones de pantalla y es fácil de instalar.
La barra lateral está construida por varios conkys y es fácil de expandir.

Dispositivos
- Fecha / Hora
- Procesador
- Memoria
- Red
- Batería
- Sistema

prerrequisito

- conky-all debe estar instalado
$ sudo apt-get instalar conky-all

instalación

Descargue o clone xtrose Conky desde GitHub:
$ git clone https://github.com/xtrose/conky.git

Mover el directorio .conky a su directorio principal

Haga que los siguientes archivos sean ejecutables:
$ chmod +x ~/.conky/xtrose/xtrose_start
$ chmod +x ~/.conky/xtrose/xtrose_end
$ chmod +x ~/.conky/xtrose/xtrose_UHD/xtrose_start
$ chmod +x ~/.conky/xtrose/xtrose_FullHD/xtrose_start

Inicie xtrose Conky desde la consola:
$ bash ~/.conky/xtrose/xtrose_start

Diviértete probando
