xtrose Media Studio
Autor: Moses Rivera
Web: https://xtrose.com
Mail: media.studio@xtrose.com



Baue dir deine eigene Conky Sidebar mit xtrose Conky.
xtrose Conky kann mit mehreren Display-Auflösungen umgehen und ist einfach installiert.
Die Sidebar wird durch mehrere Conkys aufgebaut und ist einfach zu erweitern.



Bauteile
- Datum / Uhrzeit
- Prozessor
- Arbeitsspeicher
- Netzwerk
- Batterie
- System



Voraussetzung

conky-all muss installiert sein
$ sudo apt-get install conky-all



Installation

Download oder Klone xtrose Conky von GitHub:
$ git clone https://github.com/xtrose/conky.git

Verschiebe das Verzeichnis .conky in dein Home Verzeichnis

Mache folgende Dateien ausführbar:
$ chmod +x ~/.conky/xtrose/xtrose_start 
$ chmod +x ~/.conky/xtrose/xtrose_end 
$ chmod +x ~/.conky/xtrose/xtrose_UHD/xtrose_start 
$ chmod +x ~/.conky/xtrose/xtrose_FullHD/xtrose_start 

Starte xtrose Conky über die Konsole:
$ bash ~/.conky/xtrose/xtrose_start 
 


Viel Spaß beim testen
