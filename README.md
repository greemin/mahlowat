mahlowat - Listentool
========

Fork des mahlowat-tools von hszemi. 
Zielstellung ist ein Interface für die Listen 
zum Eintragen ihrer Anworten und Erläuterungen, 
damit diese dann in den eigentlichen mahlowaten 
importiert werden können.

Implementierung
---------------

PHP und JavaScript, alles im Quelltext.
Benutzt bootstrap by Twitter und jQuery.

Funktionen
----------

Auswahlmöglichkeiten:
* Zustimmung
* Ablehnung
* Neutral

Den Listen ist bewusst keine Gewichtung der Thesen möglich.

### Installation


Zur Installation wird einfach der Ordner mit allen Dateien auf den Webspace hochgeladen.

Ganz recht, das Ganze funktioniert ohne Datenbankanbindung. Dafür müssen für die Statistik Dateien verändert werden.
Hierzu muss der Prozess des Webservers Schreibrechte für den 'data'-Ordner bekommen. 
Bei Problemen sollte es funktionieren, über den FTP-Client die Ordnerrechte auf '777' zu ändern. 
Hinweis: Dies kann ein Sicherheitsrisiko darstellen, sollte aber nicht.


Lizenz
------
Dieses Projekt benutzt jQuery. jQuery ist unter der MIT LICENSE lizensiert (LICENSE-jquery.txt)

Dieses Projekt benutzt bootstrap. bootstrap ist unter der MIT LICENSE lizensiert (LICENSE-bootstrap.txt)