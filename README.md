# tutorBot
tutorBot ist ein Bash-Skript, das den Inhalt einer Datei ausliest
und die ungeraden und geraden Zeilen jeweils in einen Array liest.

Der Aufbau der Datei sollte dabei folgendem Schema folgen:
Ungerade Zeilen sind Fragen,
gerade Zeilen sind Antworten zu der davor gestellten Frage.

Das Skript stellt dem User sodann eine zufällig ermittelte Frage
aus dem Fragen-Array und vergleicht die gegebene Antwort mit dem
entsprechenden Index des Antwort-Arrays.

Weitere Funktionen:
Beendet man das Skript mittels Eingabe von SAVEEXIT werden
- die noch nicht beantworteten Fragen und Antworten und
- die Fragen und Antworten, die man in der laufenden Session nicht sofort richtig beantwortet hat
jeweils in eine eigene Datei in das Home-Verzeichnis des Skript-ausführenden Users (nicht root!) gespeichert.

Bei erneutem Skript-Aufruf wird der User dann gefragt, ob er 
1) nur die fehlerhaften Fragen wiederholen,
2) nur die übrigen Fragen beanworten oder
3) mit der ursprünglichen Datei fortfahren will.

Der Fragenkatalog beinhaltet derzeit Grundlagen-Fragen zu Linux und Computer-Netzwerke.

# subnetBot
subnetBot ist ein Bash-Skript, das Subnetze ausrechnen kann und dem
Nutzer auch private IPs samt Subnet Mask zum Selber rechnen gibt.

Zum zweiten Fall ist die Möglichkeit der Eingabekontrolle und der
Anzeige der Lösung vorgesehen.
