Installieren:
-------------

Alle Dateien und Ordner in den Root Ordner kopieren (gitignore mergen). Mit `vagrant up` die Box starten.
Mit der IP-Address `192.168.13.37` kann man nun die Webseite Aufrufen, 
vorausgesetzt man hat die Abhängigkeiten (composer) usw. vorher installiert.
Alle befehle wie composer oder cache clear sollten in der Box passieren, 
da ggf. Service nicht existieren oder Rechte nicht vorhanden sind.

Vagrant Befehle:
----------------

```bash
vagrant up # virtual box starten (beim ersten mal wird auch vagrant provsion ausgeführt)
vagrant ssh # in die virtual box per ssh verbinden
vagrant provision # virtual box updaten
vagrant halt # virtual box stoppen
vagrant destroy # virtual box zerstören
``` 